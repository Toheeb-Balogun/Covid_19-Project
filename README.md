# Covid_19-Project
 This repository outlines data science techniques and offers critical analysis for selecting appropriate actions. It aids decision-making by considering various factors, ensuring effective methodology choices

# INTRODUCTION
This is a dummy dataset that imitates the characteristics of data collected from hospital patients during covid-19 pandemic.

*Discalimer*: The dataset used for this analysis is a dummy dataset.

# PROBLEM STATEMENT
This dataset comprises twenty-one columns, encompassing the input column that encapsulates information regarding the severity of COVID for specific individuals. The aim of this project is to build a ML model and train the model with the available features to predict the severity of Covid in individuals. The scale of severity in individuals ranges from
Level 1: Lowest level of covid detected (asymptotic)
Level 2: Mild symptoms*
Level 3: Moderate symptoms* 
Level 4: Moderate to severe symptoms* 
Level 5: Severe symptoms* 
Level 6: Critical symptoms
Level 7: Life threatening conditions

# ROUTINE EXPLORATION OF THE DATASET AND FEATURE ENGINEERING
All important and useful libraries were imported, it is important to note that it is conventional to import all libraries at the start of the script in a data science project as this allows for a structured and logical workflow. This process is iterative as you would usually realize that a library that has not been imported is needed in your workflow. This is not due to poor planning, it is just natural as you come across challenges that are not envisaged in your project planning phase. Flexibility is among the core skills of a data scientist. This is then followed by a routine exploration of the dataset.
Luckily, all columns in the dataset seems to be suited for a ML model building and there are no missing values in the dataset. An observed challenge is that the responses for this dataset was created using numbers to elicit response, although a data dictionary that explains all variables exist. Due to the quantitative nature of numbers, there is a possibility that an arbitrary ordering may have been introduced in the dataset. This issue is analogous to the drawback of label encoding (Hancock & Khoshgoftaar, 2020).

![]()
![](https://github.com/Toheeb-Balogun/Covid_19-Project/blob/main/description%20of%20data.info.png)
