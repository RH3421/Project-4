# Is it Pneumonia?

![image](https://github.com/RH3421/Project-4/blob/main/Images/Header.png)

## Background
Globally, 1 in 71 children contract pneumonia every year. Unfortunately, pediatric pneumonia is also frequently fatal resulting in an estimated 2,200 deaths per day worldwide. To diagnose pediatric pneumonia highly skilled physicians, such as pediatric radiologists, are needed to interpret the medical imaging. However, the distribution of these providers is highly disparate globally. 

## Business Problem
Countries with few pediatric radiologists per capita may have potentially higher risks of delays in diagnosis and corresponding treatment failures. Higher costs and interventional risks may also be worsened. Thus, our team endeavored to produce a diagnostic support tool, leveraging machine learning to speed and improve diagnosis of pediatric pneumonia. We believe our diagnostic support tool will be particularly useful in helping healthcare providers in countries with few pediatric radiologists per capita.

## Data Understanding
![image](https://github.com/RH3421/Project-4/blob/main/Images/Normal%20v%20PNA%20CXR.png)
We used 5848 pediatric chest xrays to develop a diagnostic support tool that can differentiate between a normal chest xray (CXR) and a chest xray in a pediatric patient with pneumonia. There were 1575 normal CXR, 4273 pneumonia CXR. Recall was the metric of choice as failure to properly diagnose pneumonia (or false negative) could potentially be fatal to the child. Using recall allows us to try to reduce these false negatives.

## Modeling
We used a convolutional neural network (CNN) to developed our diagnostic support tool as they’re good for image classification, especially when geared towards color images.

## Results
Our diagnostic support tool achieved 99% recall.

## Conclusions
Utilization of a diagnostic support tool to accelerate identification of pediatric pneumonia without adding strain to hospital staff is of enormous value. This diagnostic support tool identifies pediatric pneumonia with high performance. This diagnostic support tool could be particularly valuable in underserved communities around the world where pediatric radiologists are scarce.

## Future Considerations
With additional resources and data this diagnostic support tool can be further improved and may be applicable for evaluation of adult chest xrays. Additionally, incorporation of clinical data, such as vitals signs and blood lab tests, should further improve the performance of this diagnostic support tool.

## For More Information
View the full model via the [Jupyter Notebook](https://github.com/RH3421/Project-4/blob/main/Main_Notebook.ipynb).


