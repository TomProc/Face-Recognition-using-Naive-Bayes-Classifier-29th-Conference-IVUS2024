# Face Recognition with Naive Bayes Classifier
The project was published in 29th Conference Information Society and University Studies held in Kaunas, Lithuania, May 2024
[Face recognition IVUS conference 2024.pdf](https://github.com/user-attachments/files/19938177/Face.recognition.IVUS.conference.2024.pdf)

[CERTIFICATE OF PARTICIPATION_paper48.pdf](https://github.com/user-attachments/files/19938181/CERTIFICATE.OF.PARTICIPATION_paper48.pdf)


## About the Project

This project presents a face recognition system based on:
- **Principal Component Analysis (PCA)** for feature extraction
- A custom implementation of the **Naive Bayes classifier** for classification

The system was trained and tested on a popular dataset containing photos of real people, achieving an accuracy of around **74%**.
https://www.kaggle.com/datasets/atulanandjha/lfwpeople

## Steps:

1. **Prepare the Data**
   - Load and clean a dataset of face images.
   - Resize and standardize the images to make processing easier.

2. **Extract Features**
   - Reduce image complexity using **PCA**, keeping only the most important information.

3. **Train the Model**
   - Implement a simple **Naive Bayes classifier**.
   - Train it using the extracted features.

4. **Evaluate Performance**
   - Check how well the model recognizes faces it hasn't seen before.
   - Analyze the results with accuracy scores and confusion matrices.
