# Cervical Cancer-Prediction Using XG-boost algorithm

Cervical Cancer kills about 4000 women in the US and about 300,000 women in the worldwide annually. By leveraging machine learning and ai cervical cancer death rate can be dramatically reduced with early detection and diagnosis.

In this project I used extreme gradient boosting algorithm(XG-boost algorithm). This algorithm can be used for regression and classification tasks. This algorithm offers solid robustness and high computational efficiency.

## Project Goal

* In this project an XGBoost model is build and trained to predict cervical cancer in 858 patients.

* The dataset was collected at 'Hospital Universitario de Caracas' in Caracas, Venezuellaand contains demographic information, habits and historic medical records of 858 patients.

*  Cervical Cancer kills about 4000 women in the US and about 300,000 women in the worldwide annually. Due to increased medical screening, cervical cancer death rate has been reduced by 74% from 1955 to 1992.

*  Studies have shown that high sexual activity Human Papilloma Virus(HPV) is one of the key factors that increases the risk of having cervical cancer.

*  The presence of hormones in oral contraceptives, having many children, and smoking increase the risk for developing cervical cancer, particularly in womeninfected with HPV. Also, people with weak immune systems(HIV/AIDS) have high risk of HPV.

<br />


  
![Diagram](https://github.com/batuhan6/Cervical-Cancer-Prediction/assets/32600613/df9bb48a-b183-45ba-bd6f-c76e7ec5fc79)

<br />

## Project steps

1- Perform exploratory data analysis.

2- Perform data visualization.

3- Prepare the data before training

4- Understand the theory and intuition behing XG-Boost algorithm

5- Train and Evaluate XGBOOST Classifier


Libraries used for this project are pandas(For dataframe manupulation), numpy(For multidimensional array manipulation), seaborn(For data visualization), matplotlib(For data visualization) and plotly(For interactive data visualisation).

There are four main techniques try to diagnose cancer. Hinselmann, Schiller, Cytalogy, Biopsy. I focused on Biopsy in this project.

All these features play a key role in causing cervical cancer in women. We will feed these features to our model and train it. Then the model will try to predict for us the Biopsy variable for us. 

![birleştirilmiş](https://github.com/batuhan6/Cervical-Cancer-Prediction/assets/32600613/013548a2-c72d-412e-af22-49b47226df6a)

<br />
<br />

Heat map is created to see the correlations between all features. Reading correlations from heat maps is easier compared to reading correlations from tables. 


![1](https://github.com/batuhan6/Cervical-Cancer-Prediction/assets/32600613/eead5498-f673-48f4-b749-aedde60d293b)
![2](https://github.com/batuhan6/Cervical-Cancer-Prediction/assets/32600613/741e2e64-bdee-46c8-90c1-8cc35ba2ee89)

<br />
<br />

Histogram distributions for all the features are created.

![hist_command](https://github.com/batuhan6/Cervical-Cancer-Prediction/assets/32600613/ce3cfaa2-eb80-4627-955e-72863091c733)
![hist1](https://github.com/batuhan6/Cervical-Cancer-Prediction/assets/32600613/9ea54f4b-92d4-4532-af32-e6755b30fa05)
![hist2](https://github.com/batuhan6/Cervical-Cancer-Prediction/assets/32600613/c062e083-90a1-4104-b701-f16db86d5f26)


 
*  Age distribution shows us that participants in this study are mainly between 20 and 30 years old.

*  Biopsy distribution shows that there are a lot of people that are not diagnosed with cancer according to biopsy diagnosis.

*  Histogram of first sexual intercouse is bell curved and shows us that first sexual intercouse is mostly between 15 and 20 years old. 

*  When we look at histogram of number of pregnancies. Mostly people have 1 to 3 kids. Max number of pregnancies is set at 11. 




