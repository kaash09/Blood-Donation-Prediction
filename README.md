## The dataset from the Blood Transfusion Service Centre
### Overview
Donating blood has been practiced for a very long time. The first successful transfusion between two dogs was documented in 1665, while the first transfusion of human blood for medicinal purposes took place in 1818. Donated blood is still an essential resource in times of need.
Our dataset comes from a Taiwanese mobile blood donation vehicle. As part of a blood drive, the Blood Transfusion Service Centre makes blood drives to several institutions.

### Problem Synopsis
Our goal is to forecast which donor will donate blood when the car returns to campus.
### Approaches
Given that we are requested to estimate the likelihood that a specific donor would give blood (a binary variable), we employ multiple distinct classification model like: Random Forest, Gradient Boosting (XGBBoost), Logistic Regression, etc.
As our assessment metric, we utilise Accuracy Score, Precision Score and F1 score, to determine which model to apply for the test dataset prediction.
### Outcome
By utilising the metric, it becomes out that the XGB model received the highest score. Our Accuracy on the test dataset, using the XGB model, was 0.75.
