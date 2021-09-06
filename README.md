
<img align="left" width="350px" src="https://github.com/zahraghorbani/nafta/blob/main/NAFTA_Logo.jpg" />


# Oil Spill Detection and Segmentation

<img align="center" width="700px" src="https://github.com/zahraghorbani/nafta/blob/main/Summary.PNG" />


## Introduction 

This repository presents project Nafta, which focuses on oil spill detection and segmentation. In addition, YOLOv3 model is implemented to detect oil rigs and vessels. All models trained on the Nafta dataset can be downloaded [here][Models]. Please read the following article for more detailed information about the project and procedures. 

### Article 

 Please cite this article if you use the dataset, model or method(s), or find the article useful in your research:

  [Monitoring offshore oil pollution using multi-class convolutional neural networks][Paper1]
  
  
 Citation: Ghorbani Z., Behzadan A.H. (2021), “Monitoring Offshore Oil Pollution Using Multi-Class CNNs”, Environmental Pollution, 289: 117884.
 


## Nafta Dataset 

The Nafta dataset contains 1,292 images. In total, 70% of images are taken by drones (low altitude), 16% by satellites (high altitude), and the remaining 14% from first-person views. There are 1,431 instances of the “oil spill” class, 959 instances of the “vessel” class, and 316 instances of the “oil rig” class (See the Venn Diagram Below) 

[Download the Dataset]


<img align="center" width="300px" src="https://github.com/zahraghorbani/nafta/blob/main/DATASET.PNG" />



## Oil Spill Classification 

VGG16 architecture is modified and fine tuned for oil spill classification. You can download the trained model [here][VGG16].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/Classification.PNG" />



## Oil Spill Semantic Segmentation

Pyramid Scene Parsing Network (PSPNet) architecture is modified and fine tuned for oil spill semantic segmentation. You can download the trained model [here][PSPNet].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/PSPNet.PNG" />


## Oil Spill Instance Segmentation

Mask R-CNN architecture is modified and fine tuned for oil spill instance segmentation. You can download the trained model [here][Mask R-CNN].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/Mask%20RCNN.PNG" />


## Vessel and Oil Rig Detection 

YOLOv3 model is used for vessel and oil rig detection. You can download the trained model [here][YOLOv3].

<img align="center" width="1300px" src="https://github.com/zahraghorbani/nafta/blob/main/Vessel%20and%20rig%20detection.PNG" />








[Paper1]: https://www.sciencedirect.com/science/article/abs/pii/S0269749121014664 
[Download the Dataset]: https://drive.google.com/drive/folders/1bnTM3WqSa6pFIQ_Wikzxf5HwV0J4t_Ko?usp=sharing
[Masks]: https://drive.google.com/drive/folders/1cXkwEDM9P65_2SPxEzoCpoo6-R_skig5?usp=sharing
[Annotations]: https://drive.google.com/drive/folders/1ti97Q6f78nYo29_1gP0zLhJUAgs-_cul?usp=sharing
[Models]: https://drive.google.com/drive/folders/1Q_J3UO96GHecrTBfYOMggAwgshPYAnav?usp=sharing
[Mask R-CNN]: https://drive.google.com/drive/folders/12mluR5B4ops2vbdzUirw6yToBiidEgkG?usp=sharing
[PSPNet]: https://drive.google.com/drive/folders/1Rb9QgJhsp2hgxU3kXlf4EYFyD_Yt4j64?usp=sharing
[VGG16]: https://drive.google.com/drive/folders/1Fkv6t45LOuguG7-TCgKv6p0NoVnJk33Q?usp=sharing
[YOLOv3]: https://drive.google.com/drive/folders/1277Hn0kEcOWU6-1W6X-OMHc_wYy9_Cjh?usp=sharing



