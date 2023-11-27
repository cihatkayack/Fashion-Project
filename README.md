# Clothing Feature Extraction and Classification

## Authors
- Cihat Kaya
- Hüseyin Onur Taştan
- Erdem Akdağlı

Izmir Democracy University, Electrical Electronics Engineering Department

## Abstract
This project focuses on the development of an algorithm for classifying clothing types in the fashion industry using Convolutional Neural Networks (CNN). The algorithm aims to help clothing companies understand potential buyer profiles, target sales to specific niches, and enhance user experience. The study evaluates various CNN models, including ResNet152, VGG16, VGG18, and YOLO, using datasets sourced from platforms such as Kaggle and GitHub.

## Keywords
Fashion, Classification Algorithms, Convolutional Neural Networks, Data Analysis, Clothing Classification

## 1. Introduction
This study emphasizes the significance of an algorithm capable of identifying and classifying clothing items. The proposed algorithm can assist clothing companies in understanding buyer profiles, tailoring sales strategies, and enhancing user experience. In the context of the growing online fashion market, AI approaches for clothing classification are crucial for increasing sales and user understanding. The study utilizes CNN models, including ResNet152, VGG16, VGG18, and Inception, with a dataset that facilitates comparison between major classification methods.

## 2. Dataset Analysis and Selection
Large datasets from sources like Kaggle and GitHub were initially examined. The study focuses on a dataset containing high-resolution images and comprehensive category labels of clothing products. To simplify training, the dataset's 143 main classes were reduced to 6 more comprehensive master categories.

## 3. Working Process
The working process involved data discovery, preparation, analysis, and visualization. The selected clothing types were pre-processed to create a suitable dataset for training the chosen CNN model. The model was optimized, and its performance was evaluated.

### 3.1 Data Discovery and Preparation
A Kaggle dataset named 'fashion-product-images-dataset' was used, containing information about clothing products, including categories, colors, genders, and other attributes.

### 3.2 Data Analysis and Visualization
Distribution of product types in the 'styles.csv' file was examined to focus on specific clothing types for the project.

### 3.3 Data Preprocessing
Visual data related to selected clothing types were processed to create a dataset suitable for training the CNN model.

### 3.4 Model Selection and Design
ResNet152, VGG16, VGG18, and Inception were chosen among important CNN models for clothing classification.

### 3.5 Performance Evaluation
The trained model's performance was evaluated with metrics such as accuracy.

### 3.6 Training Optimization
The training process was optimized by selecting specific loss functions and optimization algorithms.

## 4. Conclusion and Future Studies
The study aims to enhance garment classification algorithms in the clothing industry. Results demonstrate the accuracy of certain models in classifying clothing types. Future work may focus on using more datasets, exploring new model architectures, and optimizing the training process further.

## 5. References
- [Dataset Source](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)

1. Pereira, A. M., Moura, J. A. B., Costa, E. D. B., Vieira, T., Landim, A. R., Bazaki, E., & Wanick, V. (2022). Customer models for artificial intelligence-based decision support in fashion online retail supply chains. Decision Support Systems, 158, 113795

2. He, T., & Hu, Y. (2018). FashionNet: Personalized outfit recommendation with deep neural network. arXiv preprint arXiv:1810.02443

3. Chakraborty, S., Hoque, M. S., Rahman Jeem, N., Biswas, M. C., Bardhan, D., & Lobaton, E. (2021, July). Fashion recommendation systems, models and methods: A review. In Informatics (Vol. 8, No. 3, p. 49). MDPI.

4. Lu, Z., Hu, Y., Chen, Y., & Zeng, B. (2021). Personalized outfit recommendation with learnable anchors. In Proceedings of the IEEE/CVF conference on computer vision and pattern recognition (pp. 12722-12731).
  
5. Bhure, B. P., Bansod, P. T., Amgaokar, M. S., Lodiwale, S. P., Orkey, A. P., & Mohod, A. (2021). Fashion Outfit Recommendation Based on Deep Learning Model.
