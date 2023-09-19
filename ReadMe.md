# KKD Cup 2014

This is a project created as a requirement to analyse the data from the Kaggle competition [KKD Cup 2014](https://www.kaggle.com/competitions/kdd-cup-2014-predicting-excitement-at-donors-choose/overview).

The repository is structured as:

* **Exploration.ipynb:** main purpose is to get a grasp on each piece of data, compare with the metadata available at Kaggle, develop an understanding the type of information and content.
* **Preprocessed.ipynb:** all the data preparation is done on this notebook. Relevant columns are cleaned and transformed, correct data types casted and then saved as a pickle file to be used on the next notebook.
* **Assessment.ipynb:** This notebook shows the information relevant into answering what makes a project exciting and what type of KPI's can be relevant to early detect promising projects.
* **ML_Model.ipynb:** This notebook tackles the classification task for the *"is_exciting* column by ussing the knowledge of the data extracted on the Assessment notebook. 