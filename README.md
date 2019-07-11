# WeRateDogs Twitter Archive Data Wrangling Project

This project involves downloading the twitter archive of user WeRateDogs and gathering, assessing and cleaning the data (data wrangling process) to obtain clean data and analyse the data further to gain interesting insights. 

The Data Gathering process involved obtaining data from three different sources. We had to download the twitter archive file directly and import into a dataframe. The image predictions file was made available on Udacity's server. We had to use Requests library and code to download the file and save the data into a new file. Finally we had to use Twitter API called Tweepy to obtain the JSON data of each tweet and save it to a file. We have to parse through the file to extract some more tweet information and save this to a CSV file which we finally read into another dataframe.

The Data Assessing process involved physically viewing the data in each of the dataframe and programmatically researching through various data to assess the issues that exist related to data quality or structure or tidyness. 

The Data Cleaning process involves fixing the issues we found in the data in the above step and correcting any errors. Each cleaning task is divided into Define, Code, and Test steps where we first define the cleaning task, then write the code and finally test if the clean task was successful.

Once the data has been cleaned, we will store the data in a csv file to be used again for analysis.

<b> Installation: </b>
You need to be able to open a Jupyter notebook and work in it on your computer. You will need to ensure the following packages are instaled on it:
1. NumPy
2. pandas
3. requests
4. tweepy
5. json
We can install these packages using pip or conda.
We need a word processor like Google Docs or Microsoft Word to be able to read the report.

<b> Project Assumptions: </b>
We have considered original ratings (no retweets) that have images. 

Assessing and cleaning the entire dataset completely would require a lot of time. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.

The rating numerator is greater than the rating denominator in several cases. This unique rating system is a big part of the popularity of WeRateDogs.



