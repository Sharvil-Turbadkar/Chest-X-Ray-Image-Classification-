# Chest-X-Ray-Image-Classification-
Performed Ternary Classification analysis using the patients' chest CT images to predict if a patient has COVID-19 due to pneumonia , is normal or has other pneumonia . 

The goal of this project is using the patients' chest CT images to predict if a patient has pneumonia caused by COVID-19 , normal or has other pneumonia .
This is ternary classification analysis
The Dataset is too heavily imbalanced thus rendering accuracy metric useless. We thus need to focus more on other measures like Precision Recall Curve as the majority baseline is 73.7
Reason:
To deliver adapt services to hospitals as patients with pre-existing conditions of pneumonia are more likely to visit the hospital on accounts of getting tested for COVID-19 
Some of the early studies showed specific abnormalities in the chest radiograms of patients infected with COVID-19 and pneumonia . 
I built a neural network with 3 feed-forward layers using tanh activation function obtaining a f1 score of 0.974 .Thus our network learns to classify patient condition using  x-rays

