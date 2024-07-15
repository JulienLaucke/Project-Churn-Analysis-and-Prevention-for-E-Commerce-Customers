# Churn Analysis and Prevention for E-Commerce Customers

This repository contains a comprehensive analysis of customer churn for an e-commerce business. The goal is to identify key factors that influence customer churn and to develop strategies to improve customer retention. The analysis uses machine learning techniques, particularly the Random Forest classifier, to predict churn and extract actionable insights.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Steps](#analysis-steps)
- [Results](#results)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer churn is a significant challenge for e-commerce businesses. By understanding the factors that lead to customer churn, businesses can implement targeted strategies to retain customers and reduce churn rates. This project uses a Random Forest classifier to analyze customer data and predict churn.

## Dataset

The dataset used in this analysis contains the following features:

- Age
- Annual Income
- Total Spend
- Years as Customer
- Number of Purchases
- Average Transaction Amount
- Number of Returns
- Number of Support Contacts
- Satisfaction Score
- Last Purchase Days Ago
- Target Churn
- Gender (Female, Male, Other)
- Email Opt-In (True, False)
- Promotion Response (Ignored, Responded, Unsubscribed)

## Installation

To run this analysis, you need to have Python and the necessary libraries installed. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/churn-analysis.git
```

2. Navigate to the project directory:

```bash
cd churn-analysis
```

3. Run the Jupyter notebook:

```bash
jupyter notebook e-commerce.ipynb
```

## Analysis Steps

1. **Data Preparation and Scaling**:
   - Load the dataset.
   - Split the data into features (X) and target (y).
   - Scale the features using StandardScaler.

2. **Model Training with Random Forest**:
   - Train a Random Forest classifier on the training data.

3. **Model Evaluation**:
   - Evaluate the model using accuracy, confusion matrix, and classification report.

4. **Feature Importance**:
   - Identify the most important features contributing to customer churn.
   - Visualize the feature importance.

## Results

The analysis identified the following top five features as the most significant for predicting customer churn:

1. **Average Transaction Amount**
2. **Total Spend**
3. **Annual Income**
4. **Last Purchase Days Ago**
5. **Age**

## Recommendations

Based on the analysis, the following recommendations are made to improve customer retention:

1. **Personalized Offers Based on Transaction Behavior**:
   - Engage high-value customers with exclusive offers and reward programs.

2. **Income-Based Segmentation**:
   - Target high-income customers with premium services and tailored offers.

3. **Reactivation Campaigns**:
   - Reach out to customers who haven't made a purchase in a while with reactivation campaigns.

4. **Age-Appropriate Marketing Strategies**:
   - Customize marketing messages and strategies for different age groups.

## Conclusion

The churn analysis provided valuable insights into the key factors influencing customer churn. By implementing targeted actions based on these insights, businesses can improve customer retention and effectively reduce churn rates. Continuous monitoring and adaptation of strategies are crucial for long-term success.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
