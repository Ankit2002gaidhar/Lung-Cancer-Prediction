1] Introduction 

   Lung cancer is one of the most prevalent and deadliest forms of cancer worldwide, with early
detection being critical for successful treatment and improved patient outcomes. Despite
advances in treatment, the prognosis for lung cancer remains poor, primarily due to late-stage
diagnosis. Early detection is crucial for improving patient outcomes, as it allows for timely
intervention and appropriate treatment strategies.
Conventional diagnostic methods for lung cancer, such as computed tomography (CT) scans, rely
heavily on the expertise of radiologists for interpretation. However, the subjective nature of visual
interpretation can lead to variability in diagnoses, potentially resulting in missed or incorrect
identifications of malignant nodules.

2] DataSet Used:https://www.kaggle.com/datasets/ankitgaidhar/lung-cancer-min

3]Objectives
1]The primary goal is to develop a model based on machine learning and deep learning for the
accurate classification of lung cancer based on pulmonary nodules detected in CT scans.
2]This model aims to reduce variability in nodule classification, ensuring a more consistent and
accurate assessment.
3]This analysis aids healthcare professionals in determining the severity of the condition.
4]This machine learning model is crucial for formulating effective treatment strategies and
making informed decisions concerning patient care in the context of lung cancer.

4] Overview of Model Architecture
1. Data Collection: Gather medical images like CT scans, or MRIs, X-ray scans.
2. Data Preprocessing: Clean the data to remove noise and standardize image sizes and resolutions.
3. Feature Extraction: Use CNN and its variants to automatically identify patterns indicative of lung cancer.
4. Model Training: Split data into training, validation, and test sets for training the model.
5. Model Evaluation: Assess the trained model's performance using metrics like accuracy and AUC-ROC.
6. Continuous Improvement:
Fine-tune the model based on other deep learning and machine learning techniques and
real world feedback.

5]Technology Used:
1] Python libraries such as numpy,pandas,matplotlib.
2] Tensorflow,Keras
3] CNN,VGG_NET

6]Conclusion:

We have provided an overview of the main approaches used for nodule classification and lung
cancer prediction from CT imaging data. In our experience, given sufficient training data, the
current state-of-the-art is achieved using CNNs trained with Deep Learning achieving a
classification performance in the region of low 90s AUC points. When evaluating system
performance, it is important to be aware of the limitations or otherwise of the training and
validation data sets used, i.e., were the patients’ smokers or non-smokers, or were patients with a
current or prior history of malignancy included.
