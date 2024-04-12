# Human Activity Recognition Dataset


Human Activity Recognition (HAR) is crucial in various fields, such as healthcare, sports analytics, and human-computer interaction. HAR aims to identify and classify human activities from sensor readings by analyzing sensor data. This project compares state-of-the-art deep learning and machine learning approaches for HAR, providing insights into their performance and efficacy.

## Dataset

The dataset used in this project comprises sensor data collected from wearable devices, capturing various human activities such as walking, running, sitting, and standing. Each data instance contains sensor readings from accelerometers, gyroscopes, and corresponding activity labels. 

## Approach

### Deep Learning Approaches:

In this project, we have explored a combination of deep learning architectures tailored for Human Activity Recognition (HAR). These architectures include Convolutional Neural Networks (CNN), Long Short-Term Memory networks with CNN (LSTM-CNN), Stacked LSTM, Vanilla LSTM, ISPL Inception, and Transformers with CNN. Each architecture brings its unique strengths to the task of HAR, allowing us to compare their performance and efficacy in accurately recognizing human activities from sensor data.

### Machine Learning Approaches:

In our project, we have implemented approximately 20 machine learning approaches tailored for Human Activity Recognition (HAR). These approaches encompass a wide range of traditional machine learning algorithms, including Support Vector Machines (SVM), Random Forests, Gradient Boosting Machines (GBM), k-Nearest Neighbors (k-NN), and Decision Trees, among others. Additionally, Bayesian Machine Learning techniques have been incorporated to explore probabilistic models and enhance the accuracy of activity recognition. 

## Performance Comparison

| Model Name                 | Accuracy (%) | 
|----------------------------|--------------|
| Softmax (Multinomial Logistic Regression)       | 95.9         | 
| Bayesian Logistic Regression      | 96.1         | 
| Support Vector Machine      | 96.3         | 
| CNN - LSTM                 | 93.28        |
| ISPL Inception             | 94.47        | 
| CNN                        | 96.23        | 

## Usage

This repository provides code implementations, datasets, and model architectures for HAR using deep learning and machine learning approaches. Researchers and practitioners in healthcare, sports analytics, and human-computer interaction can leverage these resources to develop robust and accurate HAR systems.


## License

This project is licensed under the MIT License.

