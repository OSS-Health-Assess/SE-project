# **REPOVITAL: Tracking OSS Project Health Through Data-Driven Metrics**  

## **Overview**  
REPOVITAL is a machine learning-based analysis designed to assess the health of open-source software (OSS) projects. With OSS forming the backbone of modern technology, ensuring project sustainability is crucial. Our approach classifies OSS projects as *Graduated* (healthy) or *Retired* (declining) using advanced data-driven techniques.  

## **Repository Structure**


- **`issues-cleanedData/`**: Contains cleaned datasets derived from issue tracking systems, prepared for analysis.

- **`issues-output/`**: Stores raw outputs from issue tracking data extraction processes.

- **`scraper-output/`**: Includes data obtained from the OSS Scrapper, capturing various project metrics.

- **`EDA-classification-on-issues-output.ipynb`**: Jupyter Notebook performing exploratory data analysis (EDA) and classification tasks on issue tracking data.

- **`EDA-on-scraper-output.ipynb`**: Notebook dedicated to EDA on data collected via OSS Scrapper, identifying trends and patterns.

- **`EDA-programming-languages.ipynb`**: Analyzes the distribution and impact of programming languages within the dataset.

- **`LSTM-model-on-scraper-and-issue-data.ipynb`**: Implements Long Short-Term Memory (LSTM) neural networks to model temporal aspects of project health using both scraper and issue data.

- **`base-case-classification-on-scraper-output.ipynb`**: Establishes baseline classification models using scraper data to assess project health.

- **`correlation-EDA-on-scraper-output_Without_Target_value.ipynb`**: Investigates correlations among variables in the scraper data without considering the target variable.

- **`correlation-EDA-on-scraper-output_with_target_values.ipynb`**: Explores correlations in scraper data with respect to the target variable (project health status).

- **`feature-selection-on-scraper-output.ipynb`**: Applies feature selection techniques to identify the most predictive metrics in the scraper data.

- **`project-status.csv`**: A CSV file detailing the health status (Graduated or Retired) of analyzed OSS projects.

- **`requirements.txt`**: Lists the Python dependencies required to run the analyses and models.

- **`transformer-model-on-scraper-and-issue-data.ipynb`**: Utilizes Transformer-based models to analyze and predict project health from combined scraper and issue data.


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
- **Advanced models like Transformers outperform traditional classifiers** in capturing OSS health trends.  
- **A combined approach using project metrics and issue data yields the most accurate results.**  

## **Future Scope**  
- Expanding BERT implementation for longer project timelines.  
- Utilizing large language models (LLMs) like GPT-4-turbo for deeper analysis.  
- Developing a real-time monitoring system for OSS project health.  

## **Team Members**  
- Shreyas Shah
- Sachin Shankar Balasubramanyam
- Priyadharshini Ganeshkumar
- Sandhya Ghanathe
- Sarika Dinesh
