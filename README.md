#Hands on Lab - World of Watson, October 2016

 <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/w2v-ibm-design.png"/>

Session Name: Building a Word2vec Model with Twitter Data Using the IBM Data Science Experience

Date: October 25, 2016, 4:00pm - 6:30pm

Place: Las Vegas, Mandalay Bay - Bayside F - 06

Blog: http://www.ibmbigdatahub.com/blog/spark-based-machine-learning-capturing-word-meanings

# Instructions:

#Step 1. Get on IBM Data Science Experience (DSX).
##Create a BlueMix Account.

1.  Go to [http://datascience.ibm.com/](http://datascience.ibm.com/)

2.  Click the signup button on the top right

 > <img src="https://github.com/ibmdataworks/datafirst/raw/master/datascientist/media/DSX Sign On.png">

3. If you have a Bluemix account you can click continue with Bluemix credentials, otherwise click create your Bluemix account and enter your email. 

4. You should get an email from "ibmacct" with your IBMid Confirmation code

 >  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/confirmation-code.png"/>

5. Then, on the next page fill in the corresponding fields and click “Create Account”

 > <img src="https://github.com/ibmdataworks/datafirst/blob/master/appdeveloper/media/image3.png" width="624" height="300" />

6. In the new page, write your email and click CONTINUE. 

>  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/enter-email.png"/>

7. Write your recently generated password and click on SIGN IN.

>  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/enter-password.png"/>

8. It will take a minute to create your account. When ready, click on Get Started.

 > You are now in the Data Science Experience landing page. Your environment is automatically set up with one Apache Spark instance and 5 GB of object storage. From here you can explore any of the tutorials, videos, sample notebooks, totorials or articles in the community.

>  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/landing.png"/>

#Step 2. Create a project 

1. Click on the left hand side "hamburger" icon and then on My Projects to see a list of your projects. You should only see a default project.

>  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/my-projects.png"/>

2. Click on the create project icon on the top right of the project list. 

>  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/create-new-project.png"/>

3. Type a name for yout project. For instance, "Word2Vec for Text Data". A Spark service and an object storage will be automatically selected as well as a container. A container is a directory on the object storage. Click on Create.

 > You are now in your new project where you can create notebooks and data assets as well as add collaborators.

>  <img src="https://github.com/IBMDataScience/word2vec/blob/master/images/new-project.png"/>

#Step 3. Get the data 

Get some tweets from December 23, 2014 from here: 

https://www.dropbox.com/sh/82rrk8di2nouf0x/AAAIMc6J9rWpu08UBLhLbHXEa?dl=0 

Note: there is no need to uncompress the file, just download the tweets.gz file to your lap top.

#Step 4. Load the data into your object storage

#Step 5. Get the notebook
