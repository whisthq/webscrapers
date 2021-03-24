# Fractal Webscraping

This repository contains Python scripts used to scrape Reddit and Quora posts and send automated DMs to scrapped usernames. We mainly use them for customer research. If using this script to do customer research, it is best to run it at a single time and try to really get as many DMs as possible out as the Reddit/Quora account will get banned within about a day, or even within a few hours.

Reddit and Quora have added a feature limiting DM-ing to X messages every Y minutes (those numbers have changed every time we attempt to scrape), which requires throttling the algorithm to sleep for Y minutes every X messages. Depending on when you're using it, you may need to experiment slightly to circumvent the Reddit/Quora barriers. 

This runs in two steps:
  - First, scrape usernames from posts and collect a list of them in a Python notebook -- there are no limitations on this step.
  - Second, run the code to iterate through the list of post and send DMs to all those users, attaching a Google Forms survey to the DM -- this is where throttling is required.

To optimize the process:
  - Create multiple accounts, at least one per subreddit to scrape (if using Reddit); they will get banned quickly.
  - Go to a subreddit like `r/learnprogramming`, `r/starterpack`, etc. and comment on people's posts to gain karma. You need 5 karma to remove the reCaptcha feature from the direct messaging feature, which allows automated DM-ing.
  - Start DM-ing on all of your accounts in parallel.
  
Repeat as many times as needed, and try to make the Google Form surveys as simple and short as possible (5-6 short-answer questions work best)!
