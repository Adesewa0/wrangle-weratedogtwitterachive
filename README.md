# wrangle-weratedogtwitterachive

In this project, I wrangled three datasets.

The first dataset was provided by Udacity, it was a csv file named twitter_archive_enhanced.csv. It contains basic information about tweets and was downloaded manually.

The second dataset was hosted on udacity server, a tsv file named image_prediction.tsv. I programmatically downloaded the file made by a neural network that classifies dog breeds.

For the third dataset, I downloaded the file "tweet_json_text" provided by Udacity incase for any reason a student cannot scrap the data from Twitter using API keys. I read the dataset line by line and select the needed columns. This third dataset contains information like the rewetet count, favorite count each tweet recieved.

Firstly, I made a copy of the original three datasets using .copy function.

During accessing the data, I found out 8 quality issues and 2 tidiness issues. I used a variety of Pandas methods to clean them up.

Then, I followed the Define, Code amd Test process and made the following cleaning efforts:

I merged the three datasets into a master variable for analysis. And later saved into a twitter_archive_master.csv file. 
