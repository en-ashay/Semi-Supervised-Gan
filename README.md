# SSGAN-for-Abdominal-Tumor-Classification
This repository contains the code and data for a deep learning model that uses SSGAN (Self-Supervised GAN) for  tumor classification. The goal of this project is to develop a highly accurate and efficient model for automated detection and classification of  tumors from medical imaging data.

Abdominal cancer is one of the leading causes of cancer-related deaths worldwide, and early detection and treatment can significantly improve patient outcomes. Medical imaging techniques such as CT scans and MRI are widely used for diagnosis and staging of  tumors, but require expert radiologists to analyze and interpret the images. Automated machine learning models have the potential to assist radiologists and improve the accuracy and efficiency of  tumor classification.

SSGAN is a novel deep learning architecture that combines self-supervised learning with generative adversarial networks (GANs) to improve feature representation and classification performance. In this project, I adapt and apply the SSGAN approach for tumor classification using a publicly available dataset of  CT scans.


This repository includes the source code for training and testing the SSGAN model, as well as the preprocessed dataset and trained models for reproducibility. I hope that this project will contribute to the development of more effective and reliable tools for  cancer diagnosis and treatment.
## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Results](#results)
* [License](#license)

## Installation

Installations are included in the notebook

## Usage

Click on the button to open the code 
<a href="https://colab.research.google.com/drive/1HgFuf2rzUtG1YZsQ7Iv3YH_9vN8nQ1CT?usp=sharing" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>



The code for this project is available in the code directory, which includes a Jupyter notebook `SSGAN_for_Tumor_Classification.ipynb` that contains all the code for training and testing the SSGAN model, as well as the preprocessed dataset and trained models for reproducibility.

Ialso provide a results.json file that contains all the evaluation metrics and results for our SSGAN model, including accuracy, precision, recall, and F1-score. This file can be used to compare the performance of our model with other approaches for tumor classification.


## Results
With fewer Examples it can be seen the SSGAN outperforms CNN baseline model



<!-- ![Image](accuracy.png) -->
<p align="center">
  <img src="accuracy.png" alt="alt text" width="600"/>
</p>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for detail
