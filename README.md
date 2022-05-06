1. Abstract:

      Diagnosing Cardiovascular Disease survival rate within an age group is a crucial task that must be carried out with extreme precision since it is an important
      aspect for any physician. Predicting CVD at a low cost is one of the challenges in the healthcare industry. 
      Our work is based on SMOTE which predicts the survival rate of patients suffering from CVDs. We have evaluated the dataset on several classifiers using
      positive and negative classes. The experimental outcome was predicted on the imbalanced dataset which was overcome by SMOTE. Our study uses the LightGBM
      classifier to predict survival rates. The hyperparameters were eventually tuned to obtain more efficiency. The results show a maximum accuracy of 95%. The 
      precision and recall rates are 94% and 95% respectively. In addition, the proposed model has an F-score of 95%.

2. Objective:
      
      •	The paper’s fundamental goal is to illustrate the significance of data pre-processing in improving the overall performance of a machine learning model.
      
      •	This paper aims to predict whether or not a person will survive the rate of CVD more accurately than the already present methods.
      
      •	This work additionally exploits the overall performance of different algorithms and displays a comparative analysis of them, which includes linear                    regression, KNN, random forests, SVM, and XGBoost.

3. Obserations and Conclusion:
      Every year, many deaths occur because of CVD. This paper has tried to predict the chances of patients suffering from CVDs with maximum frequency. To increase 
      the model's efficiency, we have focused on a very common problem: the unbalance in the dataset. It was observed that by the use of SMOTE, the accuracy of the 
      model can be drastically increased. By tuning the hyperparameters of the LightGBM classifier, we obtained an accuracy of 94.69 %( ~95% approx.). The SHAP values 
      were calculated globally and locally to explain the impact of each feature on the model, as well as the symptoms of each patient that led to their associated 
      diagnosis. From the SHAP value plots, we can conclude that:
      
      •	Older patients are more at risk of having CVD.
      
      •	Patients with low BMI scores are less likely to suffer from CVDs.
      
      •	Patients with smoking habits are at a higher risk to suffer from CVDs.
      
      •	High Avg. glucose level also increases the risk of CVD.
      
      •	Males are more likely to have CVD than females.  
      
      •	Self-employed patients are less likely to suffer from CVDs.
