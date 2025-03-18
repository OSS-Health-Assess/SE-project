# **REPOVITAL: Tracking OSS Project Health Through Data-Driven Metrics**  

## **Overview**  
REPOVITAL is a machine learning-based analysis designed to assess the health of open-source software (OSS) projects. With OSS forming the backbone of modern technology, ensuring project sustainability is crucial. Our approach classifies OSS projects as *Graduated* (healthy) or *Retired* (declining) using advanced data-driven techniques.  

## **Key Features**  
- **Comprehensive Data Collection:** Analyzed 154 OSS projects from Apache and Eclipse foundations.  
- **Exploratory Data Analysis (EDA):** Time-series analysis to track trends in project activity.  
- **Machine Learning Models:** Implemented Logistic Regression, SVM, Decision Tree, Random Forest, LSTMs, and Transformer-based BERT models for classification.  
- **Feature Selection:** PCA and Kernel PCA identified *Commits*, *Authors*, and *Contributor Activity* as key metrics.  
- **Community Engagement Analysis:** Issue resolution and comment activity strongly correlate with project success.  
- **Statistical Validation:** Chi-square tests confirmed significant relationships between issue status and project health.  

## **Key Findings**  
- **Commits are the strongest predictor** of OSS project sustainability.  
- **Community participation (issue resolution, contributor engagement)** is crucial for project longevity.  
- **Advanced models like Transformers and LSTMs outperform traditional classifiers** in capturing OSS health trends.  
- **A combined approach using project metrics and issue data yields the most accurate results.**  

## **Future Scope**  
- Expanding BERT implementation for longer project timelines.  
- Utilizing large language models (LLMs) like GPT-4-turbo for deeper analysis.  
- Developing a real-time monitoring system for OSS project health.  

## **Team Members**  
- **Shreyas Shah** – Data Collection, PCA, ML Modeling  
- **Sachin Shankar Balasubramanyam** – Data Extraction, Feature Engineering  
- **Priyadharshini Ganeshkumar** – Literature Review, Logistic Regression Modeling  
- **Sandhya Ghanathe** – SVM Implementation, Data Visualization  
- **Sarika Dinesh** – LSTM Implementation, Issue Data Analysis  
