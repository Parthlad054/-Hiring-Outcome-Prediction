# -Hiring-Outcome-Prediction
Built and deployed a model to predict hiring decisions using real-world dataset Performed data preprocessing, feature selection, and model tuning Achieved high accuracy and deployed as a web app using Flask.  
### Abstract:-

The job market is undergoing a transformation with platforms like Indeed and Glassdoor leveraging AI to enhance job matching and user experience, while also navigating economic challenges that necessitate workforce reductions. This project focuses on building machine learning models to predict how well candidates match job postings based on features like job skills, candidate skills, experience, salary expectations, and demographic factors. Using a synthetic dataset (job_candidate_dataset.csv), the study employs exploratory data analysis (EDA), feature engineering, and advanced machinelearning models (CatBoost for regression, LightGBM for classification) to achieve high predictive accuracy. The dataset is preprocessed to handle text and categorical features, with feature engineering techniques like skill overlap and salary gap calculation to enhance model performance. The results demonstrate strong predictive capabilities, with the CatBoost model achieving an R² score of 0.9990 for regression and the LightGBM model achieving 89.62% accuracy for classification. This work highlights the potential of machine learning to streamline job matching processes, offering insights into feature importance and recommendations for further improvements.

### Problem Statement:-

The rapid integration of artificial intelligence (AI) in job platforms like Indeed and
Glassdoor, coupled with economic pressures, has led to significant workforce reductions
(e.g., 1,300 jobs cut at Indeed/Glassdoor) to prioritize AI-driven solutions. This project
aims to develop a machine learning model to optimize job-candidate matching, a core
function of such platforms, to enhance efficiency and user experience. By predicting a
job_match_score (a continuous score from 0 to 1) or a binary match_flag (indicating a
good match if ≥ 0.5), the model seeks to automate and improve the job recommendation
process, reducing reliance on human-intensive processes and aligning with the industry’s
shift toward AI integration.
