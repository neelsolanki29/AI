# Detection of Caridac Arrest using Boosting Based Classifiers


This project is used to detect accurately and rapidly whether such patients are going to suffer from cardiac arrest or not.

## Problem statement

Our problem of interest is to be able to take advantage of the high computational power available nowadays by using various Machine Learning techniques upon patients’ data, to detect accurately and rapidly whether such patients are going to suffer from cardiac arrest or not.

## Dataset

The dataset for the proposed system is the collection of the clinical database of different geographical locations like Cleveland, Hungarian, Switzerland, and Long beach.

### Dataset's description

- There are a total of 14 columns, the columns are described as followed :

| Attributes Names | Description |
| :---: | :---: |
| age | Age of the patients in years |
| sex | 1 = Male ; 0 = Female |
| cp | Type of chest pain |
| trestbps | Resting blood pressure sugar |
| chol | cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting electrocardiographic measure |
| thalach | Maximum heart rate |
| exang | Exercise-induced angina |
| oldpeak | ST Depression |
| slope | Slope of peak exercise |
| ca | Number of major vessels |
| thal | thalassemia |
| diagnosis | Cardiac arrest : 1 ; no cardiac arrest : 0 |

## Proposed Boosting Based Classifiers

Ensemble Learning is a method that is used to enhance the performance of Machine Learning model by combining several learners.

Boosting refers to any Ensemble method that can combine several weak learners into a strong learner. The general idea of most boosting methods is to train predictors sequentially, each trying to correct its predecessor.

There are mainly 3 kinds of boosting algorithms :
**1) Ada Boost Classifier** 
**2) Gradient Boost Classifier**
**3) XG Boost Classifier**

## Analysis of Results

The confusion matrix, accuracy score, precision, recall, sensitivity, F1 score, and Cohen Kappa Score are used in the evaluation process.

| Classifiers | Accuracy | Specificity | Sensitivity | Cohen Kappa Score | F1 Score |
| :---: | :---: | :---: | :---: | :---: | :---: |
| XG Boost | 91.81% | 89.89% | 94.44% | 83.39% | 92% |
| Ada Boost | 92.98% | 91.91% | 94.44% | 85.71% | 94% |
| Gradient Boost | 95% | 91.91% | 94.44% | 85.71% | 95% |

## Comparative Analysis

| Authors | Methods | Accuracy |
| :---: | :---: | :---: |
| M. Gjoreski et al. | Random Forest | 89& |

## Conclusion and Future Scope

In this work, boosting-based classifiers were proposed for the detection of cardiac arrest and promising results were achieved. Four datasets of the UCI repository are combined together and then proper exploratory data analysis and data cleaning has been done. As all 4 datasets have been combined, the problem of overfitting has been solved since the sample size of the dataset is sufficient and with the help of model tuning, an accuracy of 95% has been achieved which is exceptional for real-life situations. In order to gauge the performance of classifiers, different evaluation metrics like Accuracy, Specificity, Sensitivity, Cohen Kappa Score, F1 Score, Precision, Recall, Support, ROC, PR curves, and AUC value. The proposed system can be implemented in real-life medical scenarios and higher accuracy along with better computational time can be achieved. Even though the dataset’s sample size was large enough to attain the desired accuracy, adding more real-time patient data to the existing dataset may improve accuracy.

## Literature survey
- F. Z. Abdeldjouad, M. Brahami, and N. Matta. A hybrid approach for heart disease diagnosis and prediction using machine learning techniques. In The Impact of Digital Technologies on Public Health in Developed and Developing Countries, pages 299–306. Springer International Publishing, 2020. 
- M. Gjoreski, A. Gradiˇsek, B. Budna, M. Gams, and G. Poglajen. Machine learning and end-to-end deep learning for the detection of chronic heart failure from heart sounds. IEEE Access, 8:20313–20324, 2020. 
- A. Gupta, R. Kumar, H. Singh Arora, and B. Raman. Mifh: A machine intelligence framework for heart disease diagnosis. IEEE Access, 8:14659–14674, 2020.
- A. Javeed, S. Zhou, L. Yongjian, I. Qasim, A. Noor, and R. Nour. An intelligent learning system based on random search algorithm and optimized random forest model for improved heart disease detection. IEEE Access, 7:180235–180243, 2019.
- S. Mohan, C. Thirumalai, and G. Srivastava. Effective heart disease prediction using hybrid machine learning techniques. IEEE Access, 7:81542–81554, 2019.
- A. Nikam, S. Bhandari, A. Mhaske, and S. Mantri. Cardiovascular disease prediction using machine learning models. In 2020 IEEE Pune Section International Conference (PuneCon), pages 22–27, 2020.
- R. J. P. Princy, S. Parthasarathy, P. S. Hency Jose, A. Raj Lakshminarayanan, and S. Jeganathan. Prediction of cardiac disease using supervised machine learning algorithms. In 2020 4th International Conference on Intelligent Computing and Control Systems (ICICCS), pages 570–575, 2020.
- A. Singh and R. Kumar. Heart disease prediction using machine learning algorithms. In 2020 International Conference on Electrical and Electronics Engineering (ICE3), pages 452–457, 2020.
