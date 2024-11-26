# diabetes_ml_project1
Repo for Diabetes ML Project 1

Diabetes mellitus (DM) is a set of diseases related to how the body uses glucose, an essential source of energy for the brain, muscles, and tissues in the body. The disease is metabolic in nature, with two main subtypes – Type 1 Diabetes (T1D) and Type 2 Diabetes (T2D). T1D is an autoimmune disease where the body’s immune system attacks islet cells in the pancreas causing the halt of insulin, a hormone the body uses to allow glucose to enter cells, production in the pancreas. T2D is a common disease where the pancreas still produces insulin, but the body becomes unable to effectively use it for energy. T1D is more prevalent in children and adolescents, while T2D is more common in adults and often the result of poor lifestyle and dietary choices. 

Using UK Biobank Data, we looked at non-genetic features that contribute to both Type 1 and Type 2 diabetes. These features are crucial in risk preidction, allowing medical professionals to diagnose diabetes early-on therby mitigating complications and improving quality of life. 


sushree(readme) // we can combine and edit both to make a comprehensive one

Diabetes mellitus (DM) is a set of diseases related to how the body uses glucose, an essential source of energy for the brain, muscles, and tissues. Type 1 Diabetes (T1D) is an autoimmune disease where the body's immune system attacks islet cells in the pancreas, causing the halt of insulin production - a hormone the body uses to allow glucose to enter cells. While T1D is more prevalent in children and adolescents, early detection across all age groups can significantly improve patient outcomes and quality of life.

This project leverages machine learning techniques to predict T1D risk using non-genetic features from the UK Biobank dataset. Our analysis focuses specifically on participants of British ancestry to maintain population homogeneity and control for genetic factors. The dataset encompasses a wide range of predictive features, including demographic information (age, BMI), family history of diabetes, lifestyle factors such as smoking status, vitamin D supplementation, and significant life events or stressors like financial difficulties or family bereavements.

The technical implementation utilizes Python's robust data science ecosystem. We employ pandas for data manipulation, scikit-learn for implementing various machine learning algorithms (including Random Forest, Gradient Boosting, Logistic Regression, Support Vector Machines, and Decision Trees), and imblearn for handling dataset imbalance through techniques like SMOTE and Random Oversampling. Our preprocessing pipeline includes careful handling of missing values, feature standardization, and addressing class imbalance issues common in medical datasets.

Model performance is rigorously evaluated using multiple metrics including accuracy, detailed classification reports, confusion matrices, and ROC-AUC scores to ensure reliable predictive capability. This comprehensive evaluation approach helps ensure our models are both accurate and practically applicable in clinical settings.

To use this project, ensure you have Python installed along with the required dependencies listed in the requirements.txt file. The main analysis can be run through the provided Jupyter notebook, which contains detailed documentation of each step in the analysis pipeline. The notebook is structured to be reproducible and can be adapted for similar prediction tasks.

Our approach to T1D prediction demonstrates the potential of machine learning in healthcare, particularly in identifying risk factors and enabling early intervention. The models developed here could serve as valuable tools for healthcare providers in assessing T1D risk, though they should be used in conjunction with, not as a replacement for, clinical judgment.

