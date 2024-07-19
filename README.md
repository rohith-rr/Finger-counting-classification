# Finger Counting Classification

## Project: Classification II | Foundations of Modern Machine Learning Project

This mini-project tackles the computer vision task of identifying the number of fingers held up in front of a camera using fundamental and basic Machine Learning algorithms. The primary goal is to explain and demonstrate the strengths and weaknesses of learning algorithms such as Decision Trees, Random Forests, and Support Vector Machines (SVM). This repository is part of the course offered by iHub, IIIT Hyderabad: Foundations of Modern Machine Learning.

## Algorithms Used

1. **Decision Tree Learning**
2. **Support Vector Machines (SVM)**
3. **Random Forests**

## Observations

After applying the three methods - Decision Tree Learning, SVM, and Random Forests - it can be observed that Random Forests offer the highest accuracy for this task.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)

## Introduction

Finger counting is a fundamental task in computer vision with various applications, including gesture recognition, human-computer interaction, and sign language interpretation. This project aims to classify the number of fingers held up in front of a camera using basic machine learning algorithms. By comparing the performance of Decision Trees, SVM, and Random Forests, we gain insights into their respective advantages and disadvantages.

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/finger-counting-classification.git
cd finger-counting-classification
pip install -r requirements.txt
```
## Usage

1. **Prepare the dataset:**
   - Ensure you have a dataset of images with different numbers of fingers held up.
   - Organize the dataset into appropriate folders for training and testing.

2. **Train the models:**
   - Run the training scripts for Decision Tree, SVM, and Random Forest models.
   - Adjust hyperparameters as needed for optimal performance.

3. **Evaluate the models:**
   - Use the provided evaluation scripts to assess the accuracy and performance of each model.
   - Compare the results to determine which algorithm performs best for this task.

## Results

The following table summarizes the accuracy of each algorithm:

| Algorithm         | Accuracy (%) |
|-------------------|--------------|
| Decision Tree     | 95.16       |
| SVM               | 95.74       |
| Random Forests    | 98.29        |

Based on the results, Random Forests provide the highest accuracy for finger counting classification.

## Conclusion

In this project, we explored three fundamental machine learning algorithms for the task of finger counting in computer vision. Our experiments showed that Random Forests outperform Decision Trees and SVM in terms of accuracy. This highlights the robustness and effectiveness of ensemble methods for classification tasks.

## Acknowledgements

This project is part of the course offered by iHub, IIIT Hyderabad: Foundations of Modern Machine Learning. We thank the course instructors and assistants for their guidance and support.




