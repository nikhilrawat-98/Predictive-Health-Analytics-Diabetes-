# Predictive Health Analytics Diabetes

This project focuses on developing a predictive health analytics system using deep learning techniques, specifically targeting early detection and personalized management of diabetes using a Dense Neural Network (DNN) model. The project also includes a business strategy for launching the solution as a startup.

## Project Overview

- **Business Model**: The startup leverages neural networks to provide predictive analytics for diabetes management. It offers risk assessments, personalized health management plans, and early intervention based on user data. The platform integrates with wearable devices, allowing users to sync their health data for more comprehensive decision-making.
- **Technical Implementation**: A Dense Neural Network (DNN) was implemented to predict the risk of diabetes using health indicators such as BMI, glucose levels, and lifestyle factors. The dataset was cleaned and preprocessed, handling class imbalance with SMOTE and normalizing features. Models such as Logistic Regression, XGBoost, and DNN were evaluated for performance.
- **Tech Stack**: Python, Pandas, Scikit-learn, TensorFlow, Keras, Matplotlib

## Usage

The Jupyter notebook demonstrates the following:
1. Loading and preprocessing the dataset.
2. Training the DNN model.
3. Evaluating the model performance using metrics like accuracy, precision, recall, and ROC-AUC.

## Dataset

This project uses a diabetes-related health dataset that includes data on health indicators such as BMI, glucose levels, and lifestyle factors. The dataset was used to train the models for prediction.

### Dataset Splitting
- **Training Set**: 70%
- **Validation Set**: 15%
- **Testing Set**: 15%

## File Structure

- **`Code.ipynb`**: Jupyter notebook containing the code for the model training and exploratory data analysis (EDA).
- **`model.keras`**: Trained Dense Neural Network (DNN) model.
- **`Report.pdf`**: Group project report detailing methodology, business model, and results.
- **`Pitch Deck.pdf`**: Presentation pitch deck.
- **`requirements.txt`**: Python dependencies.

## Model and Performance

The DNN model was trained and evaluated, achieving:
- **Accuracy**: 94%
- **Precision**: Improved, with fewer false positives.
- **Recall**: 94%, minimizing missed diagnoses of diabetes.
- **ROC-AUC**: 0.99, indicating excellent performance in distinguishing between positive and negative cases.

## Installation

To run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Predictive-Health-Analytics-Diabetes.git
    cd Predictive-Health-Analytics-Diabetes
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

## Acknowledgements

The project was developed as part of an MSc course in Business Analytics.

## License

MIT License
