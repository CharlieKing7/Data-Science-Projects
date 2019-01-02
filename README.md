# My Data Science Portfolio

This is the repository that contains my data science projects. The repository is still "work in progress" and with time I will add more Jupyter Notebooks.

__Udacity Deep Learning Nanodegree Projects:__

1. __UD1_My_first_neural_network:__ In this project I coded my first feed-forward neural net from scratch and used it to predict daily bike rental ridership. Click [here](https://nbviewer.jupyter.org/github/CharlieKing7/data-science-projects/blob/master/UD1_My_first_neural_network.ipynb) to see my work.

2. __UD2_Image_classification:__ In this project, I classified images from the CIFAR-10 dataset. To do so, I preprocessed the images and trained a convolutional neural network. Click [here](https://nbviewer.jupyter.org/github/CharlieKing7/data-science-projects/blob/master/UD2_Image_classification.ipynb) to see my work.


3. __UD3_Simpson_script_generation:__ In this project, I generated Simpsons TV scripts using a Recurrent Neural Net. Click [here](https://nbviewer.jupyter.org/github/CharlieKing7/data-science-projects/blob/master/UD3_Simpson_script_generation.ipynb) to see my work.

4. __UD4_language_translation:__ In this project, I took a peek into the realm of neural network machine translation. I trained a sequence to sequence model on a dataset of English and French sentences and used it to translate new sentences from English to French. Click [here](https://nbviewer.jupyter.org/github/CharlieKing7/data-science-projects/blob/master/UD4_language_translation.ipynb) to see my work.

5. __UD5_face_generation:__ In this project, I use generative adversarial networks to generate both MNIST images and human faces. I trained everything using an AWS GPU optimized instance. Click [here](https://nbviewer.jupyter.org/github/CharlieKing7/data-science-projects/blob/master/UD5_face_generation.ipynb) to see my work.


__Other Projects:__

1. __Time Series Forecasting with XGboost:__ The aim of this notebook is consolidating the knowledge acquired with my first Kaggle Competition. In this notebook I mainly use Pandas for data wrangling. I also use some sklearn functions to prepare the features for learning. I finally perform a basic cross-validation using an Extreme Gradient Boosting Regressor. Click [here](https://nbviewer.jupyter.org/github/CharlieKing7/data-science-projects/blob/master/1_time-series-forecasting-xgboost.ipynb
) to see my work.

2. __Stacking and Text Classification (Jan-19):__ The aim of this notebook is applying common techniques that are useful when building a machine learning model. I made an extensive use of Scikit-Learn pipelines, created checkpoints to save already processed feature matrices, performed automated feature selection, used dimensionality reduction techniques (NMF and TSVD), optimized parameters with RandomSearch, abused cross-validation and implemented Stacking! . Click [here](https://nbviewer.jupyter.org/github/CharlieKing7/data-science-projects/blob/master/2_stacking_and_text_classification.ipynb) to see my work.

__Utilities:__

1. __utility1_connection:__ With this class you can query your databases using 3 lines of code. It's based on SQLAlchemy and seamlessly handles SQL Server Port Forwarding and SSH Tunnel Creation for you. I always need to convert SQL query results to pandas dataframes and I built this class to speed up my work. You can get your query results using a with/as statement. 

```python
query = "SELECT * FROM table;"

with Connection("ENV_NAME") as conn:
    query_results = conn.get_dataframe(query)
```


