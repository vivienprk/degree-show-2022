---
layout: project
studentName: "Jesse Chan"
supervisorName: "Prof. Stephen McKenna"
projectTitle: "Maximising Performance of data augmentation in deep learning"
projectImage: "JesseChan.jpg"

---
1. Update the text below in order to show off your project
2. Alter the image associated with your project in the `project_images` folder
<hr>

## Project Aim
This project will investigate the effect of different data augmentation techniques on a small dataset ranging from different sizes from 125 to 1500 and explore whether it will have any positive or negative effect depending on the size of the data set. We will also be investigating which augmentations will be viable and more valuable on a larger dataset of skin lesions, using a combination or a singular augment on an image to reduce overfitting.

## Method
We trained our convolutional neural network from TensorFlow using a dataset of skin lesions from the ISIC Challenge. The data was then split into various data set sizes ranging from 1500 to 125 and applied simple affine and flip augmentations. We then used a more extensive data set of around 10000 images and applied various augmentations to test which had the best results.


## Findings
We identified that adding augmentations to smaller dataset sizes reduces the chances of overfitting and performs better than without augmentations. We also discovered that the random crop augmentation performed the best when studying what augmentations would be the most beneficial.
