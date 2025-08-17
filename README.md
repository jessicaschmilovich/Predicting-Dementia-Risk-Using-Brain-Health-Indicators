# Predicting-Dementia-Risk-Using-Brain-Health-Indicators
This machine learning model predicts dementia risk by analyzing 1,830 patient records from a comprehensive brain health dataset. The custom decision tree architecture processes Executive Function and Global cognitive scores alongside cardiovascular risk factors (hypertension, diabetes) and age demographics, achieving 70% accuracy with a 78.6% True Positive Rate, successfully identifying 8 out of 10 actual dementia cases. The model demonstrates superior clinical utility by enabling early detection of dementia, which affects over 57 million people worldwide and costs global healthcare systems over $1.3 trillion annually. Early identification through this model allows for timely interventions that can slow cognitive decline, improve quality of life, and help families prepare for care needs. Through hierarchical decision boundaries, the model first evaluates severe cognitive impairment (scores below -0.5), then applies age-specific thresholds (65, 70, 74 years) combined with cardiovascular risk assessment. This approach captures both severe cases with profound cognitive decline and moderate cases in older populations with comorbid conditions. The implementation successfully processes mixed data types and severe class imbalance while maintaining clinical interpretability for real-world deployment. Developed as my final project for NYU GSTEM's Winston Data Scholarship.

**Features:**
- Comprehensive Data Analysis: Explores relationships between cognitive scores, age, and cardiovascular conditions through statistical analysis and visualizations
- Custom Decision Tree Model: Implements hierarchical decision-making algorithm that evaluates cognitive impairment levels before considering age and health risk factors
- Performance Metrics: Achieves 70% accuracy and 78.6% True Positive Rate, successfully identifying 8 out of 10 actual dementia cases
- Model Comparison: Demonstrates superiority over k-Nearest Neighbors approach through comparative analysis focusing on clinical utility
- Ethical Considerations: Addresses privacy concerns and psychological impact of predictive healthcare models

**Project Structure:**

TotalBrainHealthDataset.csv: Contains 1,830 patient records with 19 variables including cognitive test scores (EF, PS, Global), demographics (age, gender), cardiovascular risk factors (diabetes, hypertension, hypercholesterolemia), and brain imaging markers.

dementia_prediction_project.ipynb  
Main Jupyter notebook containing complete project:
- Data exploration and visualization showing patterns in cognitive scores and health conditions
- Implementation of custom decision tree classifier using if-else logic
- Model evaluation with accuracy and True Positive Rate calculations
- Comparison with k-Nearest Neighbors (k=9) showing importance of metric selection
- Human context discussion on ethical implications of dementia prediction
