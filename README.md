# AI and Machine Learning-Based Skin Cancer Classification

## Overview
The NHS receives approximately 1.2 million annual referrals for skin cancer, with only 659 dermatologists in England. 60% are considered urgent, but only 6% classified as malignant, which causes unnecessary strain on the NHS. This group project aimed to reduce the number of unnecessary referrals by developing a mobile application, intended as a tool for general practitioners (GPs), to classify benign and malignant skin lesions.

Current models have shown potential for diagnostic support; however, there are concerns about transparency in results and bias towards lighter skin tones due to the lack of diversity in training datasets. Therefore, the project also investigated approaches to mitigate these common issues.

## My Contribution
The key responsibilities for my role was as follows:
- Developed a machine learning classification model to classify skin lesions, using deep learning for automatic feature extraction.
- Curated a high-quality, clean image dataset to train a machine learning model.
- Collected an equal number of unclean images to run through the model and compare results.
- Ran both datasets through the model and obtained metrics for model performance.
- Optimised model parameters to assess their impact on performance.

## Methodology
Below shows the project workflow for my role:
1. Conducted a literature review looking at human assessments of skin cancer, existing technologies, deep learning algorithms in medical settings, key model parameters, and medical device regulations.
2. Collected 200 skin lesion images to train an initial classification model, provided by the project supervisor.
3. Curated a larger dataset of approximately 6000 images, equal parts benign and malignant.
4. Cleaned the dataset by removing images with significant obstructions and low-quality.
5. Separate images into two datasets - unclean and clean.
6. Develop the convolutional neural network (CNN) architecture and introduce parameters such as batch normalisation, convolutional blocks and dropout.
7. Run both datasets through the model and obtain performance metrics.
8. Adjust parameters and rerun the datasets through the model for potential improvements in accuracy.
9. Report on the results obtained for both datasets and comment on the optimal epoch for model performance.


