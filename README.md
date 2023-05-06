# HomicidePredictionModel

In recent years, crime in New Orleans has reached alarming levels, with the city being declared the ‘murder capital’ of America by the Metropolitan Crime Commission. Gaining insights into the probability of a homicide occurring in specific districts can reveal spatial and temporal patterns of violent crime, such as seasonality, clustering, and distribution. This project aims to leverage modern machine learning techniques to help identify and prevent homicides, while also maintaining awareness of the potential ethical concerns associated with machine learning models used in the criminal justice system.

This project investigates the use of machine learning to predict the likelihood of a homicide occurring in the city of New Orleans, based on electronic police reports filed during the year 2022. We employed multiple binary classification algorithms, specifically Logistic Regression, Random Forest, and Support Vector Machines (SVM), to train our models on various factors, including location, demographic, and seasonal trends, in order to classify police reports as homicides or non-homicides.

The results of this project reveal that the three models demonstrated exceptional, but varying levels of success in differentiating between homicide and non-homicide police reports. Logistic Regression and SVM showed flawless performance, while the Random Forest model had slightly lower precision and recall for the homicide class. These findings suggest that machine learning can be a powerful tool for crime analysis in New Orleans. However, further improvements can be made by refining data preprocessing techniques and incorporating additional information in the police reports to add even more precise classifications such as future prediction of a crime occurring. Moreover, experimenting with more complex models, such as neural networks that excel at capturing subtle data patterns, may lead to even better results.

In conclusion, this project highlights the potential of machine learning in crime analysis for the city of New Orleans, but it also underscores the challenges and limitations that need to be addressed. Continued research and testing are encouraged to achieve the ultimate goal of creating a safer city for all its residents.

You may find the relevant technical report, Jupyter Notebook, and dataset at the following GitHub repository: https://github.com/warabasil/HomicidePredictionModel