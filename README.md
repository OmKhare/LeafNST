# LeafNST

An Improved Data Augmentation Method for Classification of Plant Disease using Object-Based Neural Style Transfer <br/>
[Project Report](https://drive.google.com/file/d/16NUbJcSNPIigySctF38LPi9Vj-yMlZ9b/view?usp=sharing)

## Motivation
- Plant diseases significantly threaten global agriculture, impacting crop yield and food security and nearly 30% of the crop yield is lost due to plant diseases.
- Efficient identification and classification of plant diseases through computer vision techniques have become imperative for timely intervention.
- However, popular plant disease datasets often suffer from data imbalance, with certain classes underrepresented, hindering the performance of machine learning models.

| <img src="https://github.com/OmKhare/LeafNST/blob/main/Images/imbalance.jpeg" width="800"> | 
|:--:| 
| *PlantVillage Dataset Class Distribution* |

## Part 1- Developing Object-based Neural Style Transfer
- Introduced a pioneering methodology for object-based image-to-image style transfer.
- This innovative approach employs a single deep convolutional neural network that ingeniously integrates the capabilities of You Only Look Once version 8 (YOLOv8) for object segmentation with a CNN for style transfer.

| <img src="https://github.com/OmKhare/LeafNST/blob/main/Images/Pipeline%20Architecture.png" width="800"> | 
|:--:| 
| *Architecture Diagram for Part 1* |

### Publication

* Paper accepted and presented at Fourth International Conference on Innovations in Computational Intelligence and Computer Vision (ICICV 2024)
* Awarded Best Paper Award out of 70 papers presented

### Result

| <img src="https://github.com/OmKhare/LeafNST/blob/main/Images/results.png" width="800"> | 
|:--:| 
| *Results for Part 1* |

## Part 2- Using the above approach for Data Augmentation and comparing it with other SOTA Data Augmentation methods
- Building upon our previous research, we have addressed the aforementioned data imbalance issue in plant disease datasets.
- By adopting an advanced approach of CNN-based Style Transfer for data augmentation, we could generate synthetic images that more accurately represent underrepresented classes within these datasets.
- Finally, we have compared our approach of using Neural Style Transfer with other state-of-the-art Data Augmentation methods (including GANs, traditional techniques etc.) on different datasets.

| <img src="https://github.com/OmKhare/LeafNST/blob/main/Images/data-augmentation.jpg" width="800"> | 
|:--:| 
| *Architecture Diagram for Part 2* |

### Publication

* Paper accepted and published in the Discover Artificial Intelligence Journal by Springer Link
* [LeafNST: an improved data augmentation method for classification of plant disease using object-based neural style transfer](https://link.springer.com/article/10.1007/s44163-024-00150-3)

### Result

| <img src="https://github.com/OmKhare/LeafNST/blob/main/Images/Augmentation-Results.png" width="800"> | 
|:--:| 
| *Results for Part 2* |

## Authors
1. [Om Khare](https://github.com/OmKhare)
2. [Harshmohan Kulkarni](https://github.com/harshmohan07)
3. [Ninad Barve](https://github.com/ninad-barve04)
