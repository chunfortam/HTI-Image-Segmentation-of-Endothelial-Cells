Endothelial Cell Segmentation Using Deep Learning Techniques

**Overview**__
Endothelial cells (ECs) play a critical role in vascular health and are central to understanding diseases such as cardiovascular diseases (CVD), cancer, and metabolic disorders. Quantifying EC metabolism, particularly mitochondrial function, is essential for assessing cellular bioenergetics and understanding their contributions to disease progression. Traditional biochemical methods, such as measuring reactive oxygen species (ROS) and mitochondrial membrane potential, provide valuable insights but cannot capture real-time, dynamic changes in living cells.__

Holo-tomographic imaging (HTI) has emerged as a powerful label-free technique for imaging ECs and their subcellular components. HTI generates three-dimensional refractive index (RI) tomograms of microscopic samples, enabling high-resolution, quantitative imaging without fluorescent labels. This allows researchers to study living ECs and their mitochondria in their natural state over time.__

**Research Goals**__
This project focuses on applying advanced deep-learning techniques to segment endothelial cells in HTI images. By leveraging Generative Adversarial Networks (GANs), convolutional neural networks (CNNs), and newer segmentation models ResNet-34, the study aims to:__

Improve segmentation accuracy and reliability.

**Methodology**__
Deep Learning Models
DCGAN-based Segmentation: Utilizes UNet architecture with a pre-trained ResNet50 encoder for hierarchical spatial feature extraction.

**Dataset**__
145 HTI images were pre-labeled with segmentation masks for training and evaluating the models.

**Results**
Segmentation Output
Below is a visual comparison of the source image, generated mask, and real mask:
![image](https://github.com/user-attachments/assets/a3eddd4f-60ca-4562-b2ea-7fbcd4053296)
