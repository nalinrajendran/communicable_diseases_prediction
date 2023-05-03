# Communicable Diseases Prediction
Communicable disease prediction using Deep Learning and Machine Learning Algorithms (RNN and SVR).

<img width="1035" alt="Screenshot 2023-05-03 at 11 33 33 AM" src="https://user-images.githubusercontent.com/51052614/235842383-eb07fcc5-272f-4083-90d5-fbeea1394d19.png">

##                                                     MODEL DESCRIPTION


<img width="796" alt="Screenshot 2023-05-03 at 11 34 58 AM" src="https://user-images.githubusercontent.com/51052614/235842560-feb09688-fe16-48c0-a98f-d3b85e8eb91a.png">

Our study proposes a novel approach based on climate data to forecast dengue and Chikungunya cases using Long Short-Term Memory (LSTM) and Support Vector Regression (SVR). Communicable diseases, especially vector-borne diseases account for more than 17% of all infectious diseases, causing more than 700,000 deaths annually. Malaria and Dengue are the most predominant vector-borne diseases. According to WHO reports as of March 2020; Malaria cases are estimated around 219 million globally, and this results in more than 400,000 deaths every year. Most of the deaths occur in children under the age of 5 years. Dengue is the most prevalent viral infection with an estimated 96 million symptomatic cases and an estimated 40,000 deaths every year. The case count of dengue and other vector-borne diseases has been steadily increasing in the past decade. In this work, we propose a Deep Learning model called Recurrent Neural Network (RNN) to predict future disease cases, which will be a great aid for the government to take preventive measures and for hospitals to cope with the increase in medical care demands. The trends of Vector-borne disease are highly impacted by the climatic change in the region. Our model uses the past few years’ disease case data and climate data of Kerala to predict their future cases. Both the models showed excellent accuracy in predicting the cases up to the next 12 months, It has been observed that RNN performed the best on Dengue data, while SVR performed best for Chikungunya’s data compared to the other classifiers. A Graphical user interface (GUI) has also been developed for the models, which provides a user-friendly application. Our findings show that our LSTM and SVR models outperform standard statistical models and other machine-learning methods in terms of disease incidence prediction. Our suggested method has potential implications outside Kerala, including the capacity to estimate disease occurrence in other regions with similar climatic conditions. The approaches provide useful information to public health officials and policymakers, resulting in more efficient vector-borne disease management and prevention efforts.


The repo for the streamlit webapp, which was hosted on live:
https://github.com/nalinrajendran/dengue-forecast/tree/main

This contains all the files, required for the hosted app, which predicts the Dengue case-counts for the future 12 months.
