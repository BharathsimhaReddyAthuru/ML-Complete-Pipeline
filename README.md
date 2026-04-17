# ML-Complete-Pipeline
This project demonstrated an end-to-end machine learning pipeline using DVC for experiment tracking and data versioning(Using AWS S3)

# Overview
The project has two main parts:
## Experimentation
- Built a Spam Detection model
- Tested multiple algorithms: SVC, KNN, Naive Bayes, Decision Tree,Logistic Regression, Random Forest, XGBoost
- Selected the best-performing model
## Pipeline (DVC)
- Created a modular pipeline using DVC
Stages include:
1. Data Ingestion
2. Data Preprocessing
3. Feature Engineering
4. Model Building
5. Model Evaluation
- Run the full pipeline using: dvc repro


## Tools Used
1. Python, Scikit-learn, XGBoost
2. DVC (Data Version Control)
3. DVCLive (experiment tracking)
4. Git & GitHub
5. AWS S3 (remote storage)


## Key Features
1. End-to-end ML workflow
2. Multiple model experimentation
3. Pipeline automation using DVC
4. Data versioning (local + S3)
5. Experiment tracking with DVCLive

## Learnings
- Building production-style ML pipelines
- Using DVC for reproducibility
- Comparing models effectively
- Managing data and experiments
