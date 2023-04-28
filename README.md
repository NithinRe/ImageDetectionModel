# Deep Learning vs. Traditional Machine Learning for Real and Fake Image Classification

This project compares the performance of a deep learning classifier (Convolutional Neural Network) and traditional machine learning models (Logistic Regression, SVM, Decision Tree, and Random Forest) in binary image classification for real and fake images.

## Dataset and Preprocessing

1. Loaded the training and testing datasets from their respective directories.
2. Created a function to load a specified number of images and assign labels.
3. Converted images to the RGB format.
4. Formed the final training and testing sets by shuffling the data.

## Model Development

- Convolutional Neural Network (CNN) model:
  - Three convolutional layers, two dense layers, and an output layer.
  - Adam optimizer and binary cross-entropy loss function.

- Traditional machine learning models:
  - Logistic Regression
  - SVM
  - Decision Tree
  - Random Forest

## Model Training and Evaluation

1. Trained the CNN model on the training set for 100 epochs.
2. Saved the best model based on validation loss.
3. Evaluated the model's performance on the test set.
4. Compared the CNN model with traditional machine learning models.

## Results

| Model               | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| CNN                 | 50%      | 25%       | 50%    | 34%      |
| Logistic Regression | 74%      | 75%       | 74%    | 76%      |
| SVM                 | 70%      | 71%       | 70%    | 72%      |
| Decision Tree       | 67%      | 68%       | 67%    | 67%      |
| Random Forest       | 65%      | 67%       | 65%    | 63%      |

## Conclusion

The deep learning classifier model did not perform well on the binary image classification task. Further improvement to the model's architecture or training methodology may be needed to enhance its performance. The traditional machine learning models, particularly Logistic Regression, performed significantly better than the CNN model.
