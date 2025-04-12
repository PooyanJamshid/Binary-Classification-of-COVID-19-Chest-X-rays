# Binary-Classification-of-COVID-19-Chest-X-rays



## Overview  
This project focuses on the classification of COVID-19 chest X-rays into two classes: **COVID-19** and **Normal**. The classification model utilizes deep learning techniques, specifically **ResNet-18** and **ResNet-50**, to analyze and classify X-ray images.

## Dataset  
The dataset used for this project is the **COVID-19 Radiography Database**, which contains labeled chest X-ray images for COVID-19 and normal cases.

## Models Used  
- **ResNet-18**: A lightweight model for deep learning tasks, suitable for this binary classification problem.
- **ResNet-50**: A deeper ResNet variant with enhanced capabilities, used to compare performance against ResNet-18.

## Model Architecture  
- The final fully connected layer and **Layer4** of the models were unfrozen for fine-tuning.
- All other layers were frozen to retain pre-trained features.
- **Data augmentation** techniques were applied to increase the dataset's variability and improve model robustness.
- The images were pre-processed by normalizing, converting to RGB, and transforming into tensors.

## Data Visualization  
To better understand the dataset, **t-SNE** was used for dimensionality reduction and visualization. Several images from the dataset were visualized, providing insight into the separation between classes.

## Results  
The models were evaluated using a **confusion matrix** to assess performance. The results helped in analyzing accuracy, precision, and recall, ensuring the model's ability to distinguish between COVID-19 and normal X-rays.

## Constraints  
Due to hardware limitations and lack of stable internet access, the models were implemented at the code level but could not be fully trained on larger datasets. However, the required architecture and configurations for complete execution were designed and implemented.
