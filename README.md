
<img align="left" width="350px" src="https://github.com/zahraghorbani/nafta/blob/main/NAFTA_Logo.jpg" />


## Oil Spill Detection and Segmentation

<img align="center" width="700px" src="https://github.com/zahraghorbani/nafta/blob/main/Summary.PNG" />


## Introduction 

This repository presents project Nafta, which focuses on oil spill detection and segmentation. In addition, YOLOv3 model is implemented to detect oil rigs and vessels. All models trained on the Nafta dataset can be downloaded [here][Models]. Please read the following article for more detailed information about the project and procedures. 

### Article 

 Please cite this article if you use the dataset, model or method(s), or find the article useful in your research:

  [Monitoring offshore oil pollution using multi-class convolutional neural networks][Paper1]
  
  
 Citation: Ghorbani Z., Behzadan A.H. (2021), “Monitoring Offshore Oil Pollution Using Multi-Class CNNs”, Environmental Pollution, 289: 117884.
 


## Nafta Dataset 

The Nafta dataset contains 1,292 images. In total, 70% of images are taken by drones (low altitude), 16% by satellites (high altitude), and the remaining 14% from first-person views. There are 1,431 instances of the “oil spill” class, 959 instances of the “vessel” class, and 316 instances of the “oil rig” class (See the Venn Diagram Below). The dataset is available on this [OneDrive folder](https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EsiLaSYkGdNHoFcBRx9agQUByGehkQTnz8BxAGVirKEmcg?e=h8dr5S).

<img align="center" width="300px" src="https://github.com/zahraghorbani/nafta/blob/main/DATASET.PNG" />



## Oil Spill Classification 

VGG16 architecture is modified and fine tuned for oil spill classification. You can download the trained model [here][VGG16].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/Classification.PNG" />



## Oil Spill Semantic Segmentation

Pyramid Scene Parsing Network (PSPNet) architecture is modified and fine tuned for oil spill semantic segmentation. You can download the trained model [here][PSPNet]. Grondtruth masks for the oil spill class can be found [here][Masks].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/PSPNet.PNG" />


## Oil Spill Instance Segmentation

Mask R-CNN architecture is modified and fine tuned for oil spill instance segmentation. You can download the trained model [here][Mask R-CNN]. Grondtruth masks for the oil spill class can be found [here][Masks].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/Mask%20RCNN.PNG" />


## Vessel and Oil Rig Detection 

YOLOv3 model is used for vessel and oil rig detection. You can download the trained model [here][YOLOv3]. The annotations can be found [here][Annotations].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/Vessel%20and%20rig%20detection.PNG" />








[Paper1]: https://www.sciencedirect.com/science/article/abs/pii/S0269749121014664 
[Download the Dataset]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/Egfr7fAU8VxGslQBNmoyztABAewB3Kwu6FnWlojHD6r-Nw?e=PJMjdr
[Masks]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EsczYifmSpJEvKpB_QnyyNcB5QOsciKb2Le9tYNjEjc-MQ?e=t7ikdv
[Annotations]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EjfMsZrNwjBIiWHANiGb9MMBHTBj2bw8kD-cP6zNlsNcpg?e=lPdOuU
[Models]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EsXQW5WXTwVBnWw-Z1bvHr4BnCCjY4OWwHsPprrKoiUrwA?e=SdJYFe
[Mask R-CNN]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EgEuc5vr4zJHs1HLwHWpxJUBfgyKCINLjUJQ_sRUMPpXIQ?e=vaUstv
[PSPNet]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EiB66WM7ww5DlyhnDNQQ7bUB0RGRnBX-J2eaO5-Yyxd_Aw?e=b3mhwS
[VGG16]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EkicvSQBK3FPmnT6NJmrUNIB_E1GYLHEC4iSDMI8EIpy2w?e=QMtBnk
[YOLOv3]: https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/ambe3060_colorado_edu/EtqBBDL2ADpBmeSH4yIoj8UB-RFWzq5YuWqrjppjLXjH0w?e=pHh8BP

