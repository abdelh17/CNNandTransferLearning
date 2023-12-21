# CNN Based Classification and Transfer Learning

## Project Overview

This project investigates the transfer learning capabilities of Convolutional Neural Networks (CNNs) in image classification. We employed the ResNet-18 architecture to develop two models: one custom-trained on a colorectal cancer dataset and another pre-trained on ImageNet1k. Our focus was on colorectal and prostate cancer images, as well as on animal faces, to evaluate model performance in feature extraction and classification. Main techniques involved preprocessing, feature extraction using ResNet-18 models, and classification with K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) algorithms.

<h2>Screenshots</h2>
<details>
 <summary>Click to view</summary>
 <ol>
<li>Various Data</li>

![image](https://github.com/abdelh17/CNNandTransferLearning/assets/90121483/077e7aad-548a-4ed0-9d27-34a5b628ebff)

<li>Results</li>

![image](https://github.com/abdelh17/CNNandTransferLearning/assets/90121483/936fa721-1182-4346-958d-2d95227dd109)

<li>t-SNE Visualization</li>

![image](https://github.com/abdelh17/CNNandTransferLearning/assets/90121483/6822b2e2-378d-4b98-87e3-a16d59184e1b)


![image](https://github.com/abdelh17/CNNandTransferLearning/assets/90121483/2f9b027c-2456-4b8b-9cb6-d8d8838bc5a1)


![image](https://github.com/abdelh17/CNNandTransferLearning/assets/90121483/ce64bc56-1fb4-4ab0-992a-5adfb9fa1b7c)


![image](https://github.com/abdelh17/CNNandTransferLearning/assets/90121483/fb935073-1168-4ab2-8f53-4b4e14377688)


![image](https://github.com/abdelh17/CNNandTransferLearning/assets/90121483/58ee474e-fcd3-409c-8f41-30ab5a5eb7a2)

</ol>

</details>







## Requirements to run the notebook
<ol>
  <li>Navigate to the 432_project_GroupG.ipynb file</li>
  <li>Run the first code cell with the import statements</li>
  <li>If any error message is displayed, pip install the required library </li>
</ol>  

The code cell should be enough, the Colab environment comes prepackaged with all libraries needed for the project.

## Instruction on how to train/validate your model
To train and validate our mode, it is not necessary to run the entire file. Follow the steps below, in the same order.
1. Run the first code cell, with the import statements
2. Run all the cells in the "Data loading, preprocessing and basic visualization" category. This cell loads the training data and preprocesses the images
3. In Task 1, run the first 3 subcategories ("Initialization", "Training custom ResNet-18 on colorectal cancer dataset", "Evaluation"). If you wish to also visualize the extracted features from the trained model, run the "Visualization of features" category.


## Description on how to obtain the Dataset from an available download link
The dataset used in the project is composed of three sub datasets: 1 for colorectal cancer, 1 for prostate cancer, 1 for animal faces. 

Below is the link for each individual subset:  

**Animal faces:** https://1drv.ms/u/s!AilzKc-njjP7mN0LqoRZvUYONY9sbQ?e=wxWbip

**Prostate cancer:** https://1drv.ms/u/s!AilzKc-njjP7mN0M_LjB5xeAydDsrA?e=0obzsx

**Colorectal cancer:** https://1drv.ms/u/s!AilzKc-njjP7mN0NOZvxl0TPAUxmig?e=K0TpeX  

In the project, we made a zip file of these three datasets and stored it in a shared google drive asa  zip file.
At the beginning of the Python Notebook, we use the !gdown command to load the file from its host.
To download the file directly to access the data, follow the following link and unzip the file.

**Project dataset:** https://drive.google.com/uc?id=1wK7-PccXDY7tGTzQpwLD7Ok1krBxcvhi


## Instruction on how to run the pre-trained model (custom-trained model) on sample 100 images:

1. After running 'Initialization' cell the loader of 100 images is created.
2. Simply Run the last cell 'Evaluation on 100 images dataset'


|Zakaria El Manar El Bouanani|Zakaria0907|
