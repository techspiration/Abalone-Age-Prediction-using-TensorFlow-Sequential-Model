
# Abalone Age Prediction using TensorFlow Sequential Model

📌 Project Overview

This project demonstrates how TensorFlow can be used to build a Sequential Model to predict the age of abalones using the Abalone dataset. The dataset consists of various physical measurements of abalones, and the target variable ("Rings") represents their age.

We preprocess the dataset, perform label encoding, normalize the features, and train a deep learning model using Google Colab.


## 🚀 How to Use This Project

1️⃣ Open the Notebook in Google Colab

Click the link below to open the Colab notebook and follow the instructions: 📂 Open in Google Colab

2️⃣ Install Required Libraries

Run the following command in a Colab cell to install necessary dependencies:

!pip install tensorflow pandas scikit-learn matplotlib seaborn

3️⃣ Load and Preprocess the Dataset

Load the Abalone dataset from UCI Machine Learning Repository.

Perform label encoding on categorical columns.

Normalize the numerical features.

4️⃣ Build and Train the Sequential Model

Define a TensorFlow Sequential Model with Dense layers.

Compile using Adam optimizer and Mean Squared Error loss.

Train the model with 80% training data and 20% validation data.

5️⃣ Evaluate and Visualize Results

Plot the training loss vs. validation loss.

Predict and compare against actual values.

## 📥 Installation

Ensure you have the following installed in your Google Colab environment:

!pip install tensorflow pandas scikit-learn matplotlib seaborn

Or, if running locally, install them using:

```bash
  pip install tensorflow pandas scikit-learn matplotlib seaborn
```


## 📚 Key Libraries Used

TensorFlow – To build the deep learning model

Pandas – For data preprocessing

Scikit-Learn – For label encoding and data splitting

Matplotlib & Seaborn – For data visualization


HAPPY CODING !!!!!!!!!!!
