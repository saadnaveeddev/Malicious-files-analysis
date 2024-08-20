# Malicious Files Analysis

This repository contains a project for analyzing malicious files using machine learning techniques. The analysis involves preprocessing, exploratory data analysis (EDA), feature engineering, dimensionality reduction, and classification using both traditional machine learning models and deep learning techniques.

## Overview

The project focuses on classifying network traffic data into normal and attack categories. The dataset includes various features related to network transactions, which are processed and analyzed to detect malicious activity.

### Features

- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales features.
- **Exploratory Data Analysis (EDA)**: Visualizes distributions and relationships between features.
- **Feature Engineering**: Creates additional features for better model performance.
- **Dimensionality Reduction**: Utilizes Principal Component Analysis (PCA) to reduce feature dimensions.
- **Modeling**:
  - **Random Forest Classifier**: Evaluates performance using accuracy, precision, recall, and F1-score.
  - **LSTM (Long Short-Term Memory)**: A deep learning model used for sequence prediction.
  - **RNN (Recurrent Neural Network)**: Another deep learning model for sequence prediction.

## Dataset

The dataset used in this analysis consists of network traffic records with the following columns:
- `pkSeqID`: Row Identifier
- `proto`: Transaction protocols
- `saddr`: Source IP Address
- `sport`: Source Port Number
- `daddr`: Destination IP Address
- `dport`: Destination Port Number
- `seq`: Argus sequence number
- `stddev`: Standard deviation of aggregated records
- `N_IN_Conn_P_SrcIP`: Number of inbound connections per source IP
- `min`: Minimum duration of aggregated records
- `state_number`: Numerical representation of feature state
- `mean`: Average duration of aggregated records
- `N_IN_Conn_P_DstIP`: Number of inbound connections per destination IP
- `srate`: Source-to-destination packets per second
- `drate`: Destination-to-source packets per second
- `max`: Maximum duration of aggregated records
- `attack`: Class label (0 for Normal traffic, 1 for Attack Traffic)
- `category`: Traffic category
- `subcategory`: Traffic subcategory


## Usage

1. **Load Data:**

   Load your dataset using the provided CSV files.
   
3. **Preprocess Data:**

   The preprocessing steps involve encoding categorical features, scaling numeric features, and handling missing values.

4. **Run EDA:**

   Perform exploratory data analysis to understand the distribution and relationships of features in the dataset.

5. **Feature Engineering:**

   Create additional features to enhance model performance.

6. **Dimensionality Reduction:**

   Apply PCA to reduce the feature dimensions for model training.

7. **Train Models:**

   Train and evaluate both traditional machine learning models (e.g., Random Forest) and deep learning models (e.g., LSTM and RNN).

8. **Evaluate Models:**

   Assess model performance using accuracy, precision, recall, F1-score, and confusion matrices.

## Results

The models' performance metrics are reported, including accuracy, precision, recall, F1-score, and confusion matrices. Detailed results and plots are provided to visualize model performance and data characteristics.

## Contribution

Contributions are welcome! Please open an issue or submit a pull request if you have improvements or suggestions.

## License

This project is licensed under the MIT License.

## Contact

For any questions or issues and access dataset used in this project! email us

- **Saad Naveed**: [saad.naveed.dev@gmail.com]

