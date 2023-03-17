# MBTI Personality Prediction
This repository is for a machine learning project I completed as a final assignment at Hacettepe University. In this project, I implemented a prediction model without using libraries such as SciKit-Learn. Instead, I wrote functions from scratch using numpy and pandas.

The dataset used for this project is available on Kaggle (https://www.kaggle.com/datasets/anshulmehtakaggl/60k-responses-of-16-personalities-test-mbt) and includes 60,000 rows of test data from individuals who have taken the 16 personalities test (MBTI). The program was trained with 48,000 rows each time and tested with 12,000 rows using 5-fold cross-examination.

To predict personalities, I used the K-Nearest Neighbor (kNN) algorithm and implemented it using an Euclidean distance matrix. I tested the model with different k values such as 1, 3, 5, and 7. Additionally, I implemented and tested a "weighted" version of kNN.

![accuracy - k](https://user-images.githubusercontent.com/73181218/226044829-97db8549-6747-44b0-b6d0-450124a8d9b9.png)

Repeated the same process with normalized data.

![accuracy - normalization](https://user-images.githubusercontent.com/73181218/226044873-a4a5ecb6-6ecb-47b4-9602-a080ccb9ae8e.png)


I have included a code snippet that creates a confusion matrix of the results. Although accuracy results were satisfying, there is still room for improvement in terms of optimization or rewriting the model using an optimized library.




