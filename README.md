# Word2vec Models for Twitter Data (can be used with any text document too)

This is a tutorial to build Spark-based machine learning models for capturing word meanings. You can learn how to build a word2vec model using Twitter data on IBM's Data Science Experience using Apache Spark.

 <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/w2v-ibm-design.png"/>

Blog: http://www.ibmbigdatahub.com/blog/spark-based-machine-learning-capturing-word-meanings

# Instructions:

#Step 1. If you already have an account on IBM's Data Science Experience, go to step 2. If not, follow [this tutorial](https://github.com/IBMDataScience/getting-started) to create an account.

#Step 2. Create a project 

1. Click on the left hand side "hamburger" icon and then click on My Projects to see a list of your projects. You should only see a default project.

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/my-projects.png"/>

2. Click on the create project icon on the top right of the project list. 

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/create-new-project.png"/>

3. Type a name for your project. For instance, "Word2Vec for Text Data". A Spark service and an object storage will be automatically selected as well as a container with a defualt name. A container is a directory on the object storage. Click on Create.

 > You are now in your new project where you can create notebooks and data assets as well as add collaborators.

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/new-project.png"/>

#Step 3. Get the data into DSX 

1. Download (without uncompressing) some tweets from [here](https://ibm.box.com/s/mn5cenc1m6vuqm8qdwf2ddzuc4jyvpd4) to your lap top. The `tweets.gz` file contains a 10% sample (using Twitter decahose API) of a 15 minute batch of the public tweets from December 23rd. The size of this compressed file is 116MB (compression ratio is about 10 to 1).

2. Go to your recently created project on DSX and click on the add data assets + icon

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/add-data-asset.png"/>

3. Click on the Add file and select the tweets.gz file from your lap top and click on open

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/add-file.png"/>

4. Wait until the file is loaded

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/data-loading.png"/>

5. Once the file is loaded, click on Apply to add this file to your project.

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/apply-add-file.png"/>
 
  > You should see your tweets under the data assets list of your project. Your tweets are now loaded in your object storage in the container associated to your project. If your project name is "Word2Vec for Text Data", the default container name is Word2VecforTextData (unless you change to a different name on Step 2, part 3). 
 
 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/tweets-on-proj.png"/>

#Step 4. Get the notebook, open it and follow the instructions inside the notebook

1. Go back to your project and click on the create new notebook icon

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/proj-with-tweets.png"/>
 
2. Click on From URL (3rd tab), choose a name for your notebook (ex: "Spark-based ML to capture word meaning"), copy and paste this url **https://github.com/IBMDataScience/word2vec/blob/master/Spark-based%20machine%20learning%20for%20word%20meanings.ipynb** into the Notebook URL rectangle and finally click on Create Notebook.

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/create-notebook.png"/>
 
 > You are now in your new notebook and the rest of the instructions are in there.


**NOTE: to execute cells in notebooks select the cell and use Shift+enter**

--- 
#### Help us make DSX great! [Go here to take a 5 question survey about using Data Science Experience](https://www.surveymonkey.com/r/XTNCY2F) for this lab.
--- 
