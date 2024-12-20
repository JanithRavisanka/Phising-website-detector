# About the Project

Phishing URL detection is a crucial task in cybersecurity to protect users from malicious websites. This project leverages machine learning techniques to classify URLs as either phishing or legitimate. The workflow includes:

1. **Data Loading and Preprocessing**: Loading the dataset and extracting relevant features.
2. **Feature Extraction**: Manual feature extraction and TF-IDF vectorization of URLs.
3. **Model Training**: Training various machine learning models including Logistic Regression, Decision Tree, Random Forest, XGBoost, and LightGBM.
4. **Model Evaluation**: Evaluating the models based on accuracy and other metrics.
5. **Hyperparameter Tuning**: Optimizing the Random Forest model for better performance.

## Project Structure

- `215543T_ML_Assignment.ipynb`: Jupyter notebook containing the entire workflow for phishing URL detection.
- `data/phishing_site_urls.csv`: Dataset containing URLs labeled as 'good' or 'bad'.

The project demonstrates the effectiveness of combining manual and tokenized features for phishing URL detection.
