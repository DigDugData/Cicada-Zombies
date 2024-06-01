# Cicada Zombies: classification of cicadas affected with Massospora Cicadina using image data

This spring, two broods of periodical cicadas (among seven) will emerge in parts of the South and the Midwest singing their love songs. The co-emergence of these two broods has not happened since Thomas Jefferson was president. Like many animals, they, too, are susceptible to diseases. And one of those diseases they get is a fungal infection by a fungus called Massospora cicadina where a third of the body has been replaced with fungal tissue. This causes something called active host transmission causing erratic mating behavior spreading the disease (basically making other Cicada "Zombies").  Also, a possible factor is the impact of climate change since broods emerge at specific soil temperatures and this year is predicted to be the hottest year on record. In this project we identify if a cicada has the cicadina fungus or not based on image data. We use several image recognition models such as VGG16. VGG19, ResNet and Inception to tackle our problem. Our project was originally inspired by [1].   

## Team Members:

- [Douglas Stauffer](https://www.linkedin.com/in/douglas-stauffer-r/)
- [Prayagdeep Parija](https://www.linkedin.com/in/prayagdeep-parija-b2626499/)
- [Wojciech Tralle](https://www.linkedin.com/in/wojciech-tralle-9574822b9/)
- [Henry Tucker](https://www.linkedin.com/in/henryjtucker/)

## Key Stakeholders

- **Entomologists:** The phenomenon offers scientists a unique opportunity to delve deeper into the intricate world of these enigmatic vocalists. So, experts are leaping at the chance to further unravel the mysteries of cicada biogeography, evolutionary adaptations, and the ecological significance of their cyclical emergence.
- **Pharmaceutical research scientists:** Understanding the phenomenon can have potential impact on medical research on fungal diseases in humans.
- **Cicada enthusiasts:** Searching for and finding cicadas is a fun and family-friendly activity

## Project Overview

- **Dataset:** The project uses images of healthy and infected cicadas from various websites such as National Library of Medicine, GenBank, iNaturalist (https://drive.google.com/drive/folders/1jU4Hkq3MYyvOOWER5Q3_TZXKH4Qzp95g?usp=sharing)
- **Models:** Popular convolutional neural network architectures such as ResNet50, VGG16, VGG19 and InceptionV2 are used dataset for image classification.

## Key Performance Indicators (KPIs)

- F1 score,
- Model prediction precision,
- Model prediction recall,
- Model prediction accuracy.

## Neural Network Models

### Terminology

Here is a pdf file with definitions and terminology coming from neural networks and biology, which are needed for this project: https://drive.google.com/file/d/1oY2c7W0Gb51phnkFppvvztYeUuuGK-Q4/view?usp=sharing

### Very Deep Convolutional Networks for Large-Scale Image Recognition (VGG):
#### VGG16
The VGG-16 is one of the most popular pre-trained models for image classification. The VGG model has the following layers: convolutional layers = 13, pooling layers = 5, dense layers = 3. Here is the architecture of VGG-16:

![vgg16-neural-network](https://github.com/DigDugData/Cicada-Zombies/assets/122245444/18756380-95db-41e0-8f45-7a01e0233132)

#### VGG19
VGG-19, also known as VGGNet-19, is a 19-layer convolutional neural network (CNN) that can classify images into 1,000 categories. It has the same basic structure as the VGG16 model, but with three additional convolutional layers. Architecture: The 16 convolutional layers are grouped into five blocks, with a MaxPooling layer after each block. The MaxPooling layer reduces the image size by half and doubles the number of convolution layer filters. The final three dense layers in block 6 have dimensions of 4096, 4096, and 1000, respectively
![resnet_arch-ezgif com-webp-to-jpg-converter](https://github.com/DigDugData/Cicada-Zombies/assets/122245444/102acd1f-d4e8-43b2-a93e-2d70f5f67a8e)

### InceptionV2
The inception module performs convolutions with different filter sizes on the input, performs max pooling, and concatenates the result for the next Inception module. The number of layers is 42, compared to VGG16’s paltry 16 layers.

<img width="1069" alt="inception module, png" src="https://github.com/DigDugData/Cicada-Zombies/assets/122245444/d0fdc96f-e3d2-434d-be72-ee0599791f31">


## Possible Future Work

- Determine how bioclimatic variables influence infection rates in cicadas,
- Examine how climate change and warmer soil temperatures impact the timing of emergence of cicadas,
- Development of a final product possibly a mobile app.

## Acknowledgements
We would like to thank the following people for the helpful suggestions they made while we were working on this project: Roman Holowinsky, Steven Gubkin, Bailey Forster, Alec Clott, Eugeniusz Tralle, Godfrey Dzhivhuho.


## References
[1] https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9584336

[2] https://www.inaturalist.org/

[3] https://www.cicadamania.com/

[4] https://cicadas.uconn.edu

[5] https://www.npr.org/2024/05/01/1248545162/a-bizarre-fungus-is-threatening-two-
emerging-cicada-broods

[6] https://www.npr.org/2024/01/21/1225925053/billions-of-cicadas-will-buzz-this-
spring-as-two-broods-emerge-at-the-same-time

[7] https://images.cv/dataset/cicada-image-classification-dataset




 


