# Description 

This is a Python script for a web application created using Streamlit for scraping Twitter data based on a given keyword or hashtag for a given time period. 
The script uses the snscrape package to scrape data from Twitter and stores the data in a pandas dataframe. 
The dataframe can be downloaded as a CSV or a JSON file, and the tweets can be uploaded to a MongoDB database.

# Deployment

To deploy this project run

  pip install snscrape

  pip install streamlit
  
 # Environment libraries
 
To run this project you will required to add these libraries to your Environment

***import streamlit as st***

***import snscrape.modules.twitter as sntwitter***

***import datetime***

***import json***

***import pandas as pd***

***from pymongo import MongoClient***
