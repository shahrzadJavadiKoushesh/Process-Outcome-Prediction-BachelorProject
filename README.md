# Process-Outcome-Prediction-BachelorProject
This project focuses on predicting whether a purchase invoice requires approval using machine learning and deep learning techniques. The dataset used is BPIC 2019, which contains real-world event logs related to procurement processes. The goal is to build models that accurately classify whether an invoice will be approved based on historical data.

The dataset is sourced from the [BPIC 2019 Challenge](https://data.4tu.nl/datasets/dc66ef2b-cd5e-436f-a3fb-ebaf9ece54a3/1), containing event logs in JSONOCEL format. Since most machine learning frameworks work efficiently with tabular data, we converted the dataset into CSV format for preprocessing and modeling.

# Traditional Machine Learning Models:

- Logistic Regression: Provided the best accuracy among traditional models.

- Random Forest: Used for its ability to handle non-linear relationships and feature importance analysis.

- Gradient Boosting: Tried to improve classification performance using an ensemble learning approach.

# Deep Learning Models:

- CNN (Convolutional Neural Networks): Achieved the best performance due to its ability to extract hierarchical feature representations.

- RNN (Recurrent Neural Networks): Used for capturing sequential dependencies in event logs.

- LSTM (Long Short-Term Memory Networks): Evaluated for its effectiveness in handling long-term dependencies.
