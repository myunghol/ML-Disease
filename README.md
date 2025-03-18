In this repository, there are two machine learning codes for disease prediction (heart disease, COVID-19).

1. HypGB (High Accuracy GB Classifier)

1-1. Overview 
HypGB is developed as a framework for predicting Heart Disease. HypGB addresses heart disease prediction by combining LASSO feature selection and Gradient Boosting (GB) classification. It also incorporates HyperOpt hyperparameter optimization framework. HypGB enhances model accuracy by selecting relevant features using LASSO FS method and fine-tuning hyperparameters through HyperOpt. Applied to the publicly available Cleveland and Kaggle heart disease datasets, HypGB achieved accuracies of 97.32% and 97.72%, respectively, outperforming previous methods. HypGB's robust performance highlights its potential for implementation in healthcare, enabling fast and accurate heart disease diagnosis.

1-2. Main functions of HypGB
- Data Preprocessing: Handling missing values, normalization, and encoding categorical features
- Feature Selection: Using LASSO to identify the most relevant features
- Model Training: Training the GB classifier on selected features
- Hyperparameter Optimization: Using HyperOpt to find the best hyperparameters for the GB model
- Model Evaluation: Evaluating the model performance using accuracy, precision, recall, F1 score, AUC-ROC score, and computation time

1-3. How to run HypGB code
- Download the program code.
- Install the required dependencies.
- Prepare the datasets: a. Extract the datasets from the data folder. b. Preprocess the data as needed.
- Select the desired dataset folder from the model’s folder.
Open the corresponding Python code file for the individual experiments. Follow the instructions to train and evaluate the ML models using processed, feature selection and Hyperparameter optimization methods.

1-4. Datasets
- Cleveland Heart Disease
- Kaggle Heart Failure


2. COVID-19 Prediction

2-1. Overview 
The proposed framewerk addresses COVID-19 diagnosis by combining feature selection methods and machine learning classifiers, optimized using Genetic Algorithm (GA) hyperparameter optimization. This approach enhances diagnostic accuracy by identifying key features with mutual information, recursive feature elimination, and RidgeCV methods, combined using a union ensemble method. The optimized feature subsets are classified using various machine learning models, with Adaboost achieving the highest accuracy of 96.30% being optimized by GA. This methodology outperforms previous approaches and can help identify COVID-19 infections early, reducing hospital visits and aiding healthcare providers in managing resources efficiently.

2-2. Main functions 
- Data Preprocessing: Data cleaning, data normalization, and data balancing
- Feature Selection: Using individual FS methods (MIFS, RFE, and RidgeCV) to identify the most relevant features
- Union Ensemble: Union ensemble to get the ensemble optimal feature subset
- Model Training: Training the classifiers (LSVM, LR, GB, and Adaboost) on selected union ensemble feature subset
- Hyperparameter Optimization: Using GA to find the best hyperparameters for the top performing ML model
- Model Evaluation: Evaluating the model performance using accuracy, precision, recall, F1 score, AUC-ROC score, and computation time

2-3. How to run code

- Download the program code.
- Install the required dependencies.
- Prepare the datasets: a. Extract the datasets from the data folder. b. Preprocess the data as needed.
- Select the desired dataset folder from the model’s folder.
Open the corresponding Python code file for the individual experiments. Follow the instructions to train and evaluate the ML models using processed, feature selection and Hyperparameter optimization methods.
