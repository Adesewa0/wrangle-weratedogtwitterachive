# wrangle-weratedogtwitterachive
Firstly, I made a copy of the original three datasets using .copy function.

dog_ratings = dog_rate_df.copy()

images = image_predictions_df.copy()

tweet_count = tweet_json.copy()

Then, I followed the Define, Code amd Test process and made the following cleaning efforts:

I converted the tweet_id's columns from integer to string datatype for the three(3) tables and also the timestamp column from string to datetime datatype.

I removed html residues from the source column.

I dropped rows related to in_reply_to_status_id, in_reply_to_user_id, retweeted_status_user_idretweeted_status_id, and retweeted_status_timestamp then dropped their columns also plus the columns of expanded_urls and source that are not needed for this analysis.

I updated the invalid ratings denominator.

I updated the invalid ratings numerator.

I converted the None values in both dog stages columns and name column to Nan, and also the invalid dog names first to None then to Nan.

I renamed the columns jpg_url, img_num, p1, p1_conf, p1_dog, p2, p2_conf, p2_dog, p3, p3_conf and p3_dog since they are not descriptive enough.

I converted the values in p1, p2 and p3 to lowercase.

I combined the four dog stages spread across four columns into one single column.

I merged the three tables into one 











 







Storing the Data

After gathering, assessing and cleaning the data, I saved the merged data in a csv file named twitter_archive_master.csv.

This project was so challenging and educating at the same time which is part of the whole idea in the first place, I learnt a lot Wrangling the dataset.















