# Brain Weight by Head Size in Humans - Linear Regression with PyTorch
linear regression model to calculate brain weight by head size

In this notebook we'll use PyTorch to build a linear regression model to predict brain weight based on head size.

## Contents

### Data Preparation
The analysis will be based on the 'Brain weight in humans' dataset by Anubhab Swain available on kaggle.com - https://www.kaggle.com/datasets/anubhabswain/brain-weight-in-humans/data.

This dataset was compiled using a medical study conducted on a group of people.

This dataset consists of 237 records containing information on particular individuals, such as gender, age range, head size, and brain weight. Detailed information on each feature is included below. We're going to pick just one feature, head size, to see how well we can predict brain weight in relation to it.

![image](https://github.com/user-attachments/assets/ed09a82d-e27a-4858-b8a6-bd5a0db08542)

### Model Building
We have the data in place, it's time to build a model. Besides the model, we'll define a loss function and optimizer.

![image](https://github.com/user-attachments/assets/af52e4cb-2f92-4bd8-9d9e-bbde29272c4a)

### Model Training
Training the model involves two loops: a training loop, where the model learns the relationships between the features and labels, and a testing loop, where the model is evaluated.

![image](https://github.com/user-attachments/assets/3e2295b5-df95-4035-9168-19f77bc613c5)

### Model Evaluation
Let's see how our trained model performs on test data.

![image](https://github.com/user-attachments/assets/e7a8fcfa-bbfa-444a-a6bb-1337bfa4ffcd)
