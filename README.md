# Mental-Disorder-Diagnosis
Leveraging Machine Learning for enhanced mental disorder diagnosis using QEEG

## About this Project  

Mental disorders affect a significant portion of the population, and accurate diagnosis is crucial for effective treatment. Traditional diagnostic methods often rely on subjective assessments, which can be time-consuming and prone to bias. This research project investigates the potential of EEG signals, which measure electrical activity generated by eye movements, as biomarkers for mental disorder diagnosis.

## Objective
* Analyze the features extracted from EEG signals that contribute most significantly to the classification.
* Explore the potential of EEG-based diagnosis as a non-invasive and objective tool for mental health assessment.
* Develop a machine learning model that can classify different mental disorders using EEG signals.
* Evaluate the model's performance in terms of accuracy, precision, recall, and F1 score.

  
## Dataset Description:  
* The dataset consists of background information about the patients and the Quantitative values of their EEG.  
* The dataset is derived from a total of 945 patients.  
* The disorder features present 7 classes of the disorders the patients are diagnosed with.

## Model Architechture
![Architechture Diagram](https://github.com/Shashank-Pericherla/Leveraging-Machine-Learning-for-Mental-Disorder-Diagnosis/blob/main/Images/Architechture%20diagram.png)

## Methodology

* Data Acquisition:
  * The QEEG dataset has been retrieved from osf.io/8bsvr

* Data Preprocessing:
  * Cleaning and pre-processing the EEG data to remove noise.
  * Extracting important feature using feature selection.
  * Normalizing the data.
  * Over sampling the minority classes in the dataset.

* Model Development:
  * Choosing the appropriate model.
  * Training the model on a portion of the data and evaluating its performance on a separate testing set.

* Evaluation and Analysis:
  * Evaluating the model's performance using metrics like accuracy, precision, recall, and F1-score.
  * Analyzing the features with the highest importance scores to understand their role in the classification process.
### Flowchart
![Alt text](https://github.com/Shashank-Pericherla/Leveraging-Machine-Learning-for-Mental-Disorder-Diagnosis/blob/main/Images/Methodology%20Flow%20Chart.png)

## Results  

### LightGBM:
![Alt text](https://github.com/Shashank-Pericherla/Leveraging-Machine-Learning-for-Mental-Disorder-Diagnosis/blob/main/Results/LightGBM%20Training%20and%20Validation%20Loss%20Plot.png)
![Alt text](https://github.com/Shashank-Pericherla/Leveraging-Machine-Learning-for-Mental-Disorder-Diagnosis/blob/main/Results/LightGBM%20Classification%20Report.png)

### XGboost:
![Alt text](https://github.com/Shashank-Pericherla/Leveraging-Machine-Learning-for-Mental-Disorder-Diagnosis/blob/main/Results/XGBoost%20Training%20and%20Validation%20Loss%20Plot.png)
![Alt text](https://github.com/Shashank-Pericherla/Leveraging-Machine-Learning-for-Mental-Disorder-Diagnosis/blob/main/Results/XGBoost%20Classification%20Report%20.png)

## Conclusion
This project investigates the potential of using EEG signals for mental disorder diagnosis through machine learning. By exploring this approach, we may contribute to the development of more objective and accessible tools for mental health assessment.

## Future Work
* Exploring techniques to address any class imbalances or biases in the dataset could further enhance the performance of the model.
* Furthermore, investigating the generalizability of the model to unseen data from different sources or time periods would provide insights into its real-world applicability.

## Citations: 
* Dataset Source: Park, S. M. (2021, August 16). EEG machine learning. Retrieved from osf.io/8bsvr
