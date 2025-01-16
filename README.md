                                                                           <img width="908" alt="image" src="https://github.com/user-attachments/assets/9b8f63f9-5f73-495f-9b85-6f908dfc7501" />

## InsightX: Fraud Detection and Predictive Modeling

This repository hosts the code and analysis for InsightX, a comprehensive project focused on fraud detection through advanced statistical techniques and machine learning models.

### Project Overview

Fraud detection in financial transactions is critical in safeguarding economic systems. InsightX leverages real-world transaction datasets to implement, evaluate, and optimize predictive models. The project encompasses exploratory data analysis, feature engineering, and cutting-edge model evaluation to provide actionable insights.

### Key Objectives:

* Understand patterns in fraudulent transactions
* Engineer robust features for enhanced model performance
* Implement and evaluate multiple machine learning models for fraud detection
* Deliver insights for reducing financial risks

### Features

* Data Processing: Preprocessing steps include data cleaning, feature engineering, and correlation analysis
* EDA and Visualization: In-depth analysis and visualization of key trends
* Machine Learning Models:
    * Logistic Regression
    * Decision Trees
    * Random Forests
    * K-Nearest Neighbors (KNN)
* Evaluation Metrics:
    * Accuracy
    * Precision
    * Confusion Matrix
* Insightful Recommendations: Actionable findings to combat fraud effectively

### Repository Structure
├── project_code.nb.html    # Rendered notebook with comprehensive analysis
├── Final-Report.Rmd        # R Markdown file with detailed project methodology and results
├── project_code.Rmd        # Source file for generating analysis
└── README.md               # Project documentation

### Prerequisites

* Libraries and Tools:
    * R version 4.0+ with the following packages:
        * tidyverse
        * caret
        * randomForest
        * rpart
        * corrplot
    * RStudio for .Rmd file execution

### Setup Instructions:

1. Open Final-Report.Rmd in RStudio
2. Install the required R packages
3. Knit the R Markdown file to generate the report

### Usage

* Access the project_code.nb.html file to explore the analysis and results in an interactive format.
* Modify the Final-Report.Rmd file for customized analyses.
* Use the code snippets in project_code.Rmd for targeted experiments.

### Results

### Key Findings:

* High Accuracy Models: Random Forest achieved 99.99% accuracy, showcasing its robustness in fraud detection.
* Feature Importance: Transaction amount and demographic variables played a pivotal role in predictions.
* Correlation Insights: Strong positive correlations identified among high-value transactions and fraud likelihood.

### Recommendations:

* Enhance monitoring of high-risk transaction profiles.
* Incorporate real-time fraud detection models for proactive intervention.
* Refine data collection pipelines to capture nuanced behavioral patterns.

### Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes or enhancements.

### License

This project is licensed under the MIT License
