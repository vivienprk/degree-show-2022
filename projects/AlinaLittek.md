---
layout: project
studentName: "Alina Littek"
supervisorName: "Prof Stephen McKenna, Prof Emanuele Trucco &  Dr Julieta Gomez Garcia-Donas"
projectTitle: "Automating the Segmentation of Osteon Microstructures in Cortical Bone using Deep Learning"
projectImage: "AlinaLittek_seg.jpg"
---

## Project Description
The aim of this project was to investigate the feasibility of the automatic analysis of cortical bone thin sections in images by application of deep learning based segmentation. Traditional approaches to this analysis have depended heavily on manual processing, entailing a tedious and time-consuming process. Manual processing can lead to potential observer error and it is challenging to reach reliable and consistent conclusions when processing may vary between different researchers.  A deep learning tool can enable the image analysis to be done more quickly and potentially more reliably.

## Methods & Experiments
For the project, a dataset of 99 images and their corresponding masks was created including the classes fragment and intact osteons. The U-net architecture was employed and the parameters for the best segmentation model were investigated using methods such as augmentations and weighted loss. The segmentation outputs were analysed and post-processing methods implemented for the removal of noise in the images. 
A baseline for the count of intact osteons using the network predictions was investigated and two methods were compared. The average size of an intact osteon in the dataset was used to estimate the number and compared to an approach using connected component analysis of the intact class predictions only, with a threshold to separate instances.

## Project Findings
The project allowed the segmentation of the intact and fragmented osteons with good results. An IoU score of 0.555 and an accuracy of 78.9% were achieved using the U-net model with data augmentations and a custom loss function considering the weights of the data. 
The comparison of counting methods showed that better separation of the instances is necessary to achieve highly accurate results,  but good estimations could be reached without perfect segmentations. Using the average size of an intact osteon achieved acceptable results counting the intact osteons in the images. The method using connected component analysis on the intact predictions tended to undercount the instances because of the limited separation between components. A larger dataset is necessary to improve segmnetations and allow more accurate predictions.



