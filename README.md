# Is it Pneumonia?

![image](https://github.com/RH3421/Project-4/blob/main/Images/Header.png)

Authors:  [Richard Hinds](https://github.com/RH3421), [Nick Kennedy](https://github.com/nikennedy), and [Ilene Sorto](https://github.com/ileneee)

## Background
Globally, 1 in 71 children contract pneumonia every year. Unfortunately, pediatric pneumonia is also frequently fatal resulting in an estimated 2,200 deaths per day worldwide. To diagnose pediatric pneumonia highly skilled physicians, such as pediatric radiologists, are needed to interpret the medical imaging. However, the distribution of these providers is highly disparate globally. 

## Business Problem
Countries with few pediatric radiologists per capita may have potentially higher risks of delays in diagnosis and corresponding treatment failures. Higher costs and interventional risks may also be worsened. Thus, our team endeavored to produce a diagnostic support tool, leveraging machine learning to speed and improve diagnosis of pediatric pneumonia. We believe our diagnostic support tool will be particularly useful in helping healthcare providers in countries with few pediatric radiologists per capita.

## Data Understanding
![image](https://github.com/RH3421/Project-4/blob/main/Images/Normal%20v%20PNA%20CXR.png)
We used 5448 pediatric chest xrays to develop a diagnostic support tool that can differentiate between a normal chest xray (CXR) and a chest xray in a pediatric patient diagnosed with pneumonia. There were 1181 normal CXR, 3418 pneumonia CXRs. Recall was the metric of choice as failure to properly diagnose pneumonia (or false negative) could potentially be fatal to the child. Using recall allows us to optmize towards reducing these false negatives.

## Modeling
We used a convolutional neural network (CNN) to developed our diagnostic support tool as they’re good for image classification, especially when geared towards color images.

## Results
Our diagnostic support tool achieved 98% recall.

## Conclusions
Given recent events, including a global pandemic that frequently resulted in pneumonia for those affected and overwhelmed healthcare resources, having a diagnostic support tool to accelerate diagnosis without adding strain to hospital staff is of enormous value. Our diagnostic support tool accurately identifies pediatric pneumonia 98% of the time. However, it appears that our high recall rate is in part due to over-diagnosing, as there are some false positives, and very few true negatives with accuracy being a respectable 71%.

## Future Considerations
With more time and a larger dataset we believe our diagnostic support tool can be further improved and may be applicable for evaluation of adult chest xrays. We also plan to refine future iterations of our model to accurately differentiate between bacterial and viral pneumonia. Additionally, incorporation clinical data, such vital signs and blood lab tests, should further improve our diagnostic support tool.

## For More Information
View the full model via the [Jupyter Notebook](https://github.com/RH3421/Project-4/blob/main/Main_Notebook.ipynb).


