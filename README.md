# WeRateDogs-Twitter-Data-Wrangling

## Project Objectives
* Gathering, Assessing and Cleaning the data.
* Analysis and visualization of the data.
* Giving detailed reports of the steps taken to achieve the above mentioned

## Data Gathering
I successfully gathered three datasets;
* The Archived tweets file from **@WeRateDogs(‘twitter-archive-enhanced.csv’)**: this was supplied on-hand
by Udacity and I only needed to download manually. Then I read it into a pandas dataframe.
* The images prediction data **(‘images-prediction.tsv’)** : the URL to this file was given. I had to download it
programmatically using the “Requests” library from the given URL. The data was then read into pandas
dataframe.
* The API gathered data(‘tweet_json.txt’): I had to query twitter’s API to get the data needed. Data
collected include; `tweet_id`, `retweet_count`, `favorite_count` and the `followers_count`. Then the data was
stored and read into pandas dataframe.

Then, I assessed the data, did some cleaning and merging before starting my analysis.
