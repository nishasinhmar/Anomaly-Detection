# Anomaly-Detection
Random Under Sampling, Over Sampling, SMOTE, Evaluation Metrics

The data with Analomaly Dection Problem is very Imbalanced. We should analyse the whole Data first and the take out more important features.

![cm1](https://user-images.githubusercontent.com/32998362/50271649-5a98a900-045b-11e9-9e7b-5778e286e79b.png)

This is an image of the Confusion Matrix
We ought to analyse the confusion Matrix rather than the Accuracy Score, as we might end up predicting the negative class as negative but what about the positive class?
So here we come and use different evaluation metrics such as Precision, Recall, F1 Score and Support.
Here below is the way to claculate them : 

![cm2](https://user-images.githubusercontent.com/32998362/50271848-0cd07080-045c-11e9-9561-603a3030089e.png)

Under Sampling & Over Sampling (I used SMOTE)) : 

Oversampling : you duplicate the observations of the minority class to obtain a balanced dataset.
Undersampling : you drop observations of the majority class to obtain a balanced dataset, see illustration.

![us and os](https://user-images.githubusercontent.com/32998362/50272109-b9125700-045c-11e9-8ba9-a6bdee45958c.png)

This is the image showing the illustrations required for Under Sampling and Over Sampling. 

You an visit the dataset using kaggle datasets download -d mlg-ulb/creditcardfraud
