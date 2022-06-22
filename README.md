

This is an attempt at developing and deploying a fitness application that sends us new workouts (from YouTube) via an email everyday using HarperDB
and Python.

 ### The project is divided into the following parts:
- First is setting up HarperDB account and creating our cloud instance.
- Second, we setup the youtube_dl which basically extracts all the information (or the specified ones) from a YouTube workout video.
- Then, we build our app using Streamlit.
- Followed by sending emails using custom functions of HarperDB
- Lastly, we test and deploy our model. 

Technical elements used:
- Written in Python 
- HarperDB for the database 
- App made using Streamlit 
- Youtube_dl package for the youtube_extraction 
- Postman API  to build and use APIs
- Cron for scheduling tasks(sending mails) repeatedly at a specific time
