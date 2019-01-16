# Spark-based machine learning for capturing word meanings

## Data source: tweets
## Algorithms: Word2Vec, K-means, PCA
## Tools: IBM Watson Studio, Spark, Python

## Same techniques can be applied to text documents, product reviews, etc...

This is a tutorial to build Spark-based machine learning models for capturing word meanings. You can learn how to build a word2vec model using Twitter data on IBM's Watson Studio using Apache Spark.

 <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/w2v-ibm-design.png"/>

To read the blog, please click [here.](https://medium.com/ibm-data-science-experience/spark-based-machine-learning-tools-for-capturing-word-meanings-b89d2cb90a5f)

# Instructions:

## Step 1. If you already have an account on IBM's Watson Studio, go to Step 2. If not, you can create an account for free [here.](https://cloud.ibm.com/registration).

## Step 2. Create a project on Watson Studio.

## Step 3. Get the data into Watson Studio

1. Download (without uncompressing) some tweets from [here](https://ibm.box.com/s/mn5cenc1m6vuqm8qdwf2ddzuc4jyvpd4) to your lap top. The `tweets.gz` file contains a 10% sample (using Twitter decahose API) of a 15 minute batch of the public tweets from December 23rd. The size of this compressed file is 116MB (compression ratio is about 10 to 1)

2. Go to your recently created project on Watson Studio and click on the `+New data asset` icon

3. Load the file by clicking on `browse` or just dropping it

4. Once the file is loaded, click on Apply to add this file to your project.

  > You should see your tweets file under the data assets list of your project. 

## Step 4. Get a python environment and create a jupyter notebook

1. Go to your environments tab and create a `Default Spark Python 3.5 XS` environment
 
2. Click on From URL (3rd tab), choose a name for your notebook (ex: "Spark-based ML to capture word meaning"), copy and paste this url **https://github.com/IBMDataScience/word2vec/blob/master/Spark-based%20machine%20learning%20for%20word%20meanings.ipynb** into the Notebook URL rectangle and click on Create Notebook.

 > You are now in your new notebook and the rest of the instructions are in there.
