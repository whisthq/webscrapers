# Fractal Reddit Webscraping

This repository contains Python scripts used to scrape subreddit posts and send automated DMs to scrapped usernames. We mainly use them for customer research; if using this script to do customer research, it is best to run it at a single time and try to really get as many DMs as possible out there as the Reddit account will get banned within about a day, or even within a few hours.

This runs in two steps:
  - First, scrape usernames from posts and collect a list of them in a Python notebook.
  - Second, run the code to iterate through the list of post and send DMs to all those users, attaching a Google Forms survey to the DM.

To optimize the process:
  - Create multiple accounts, at least one per subreddit to scrape; they will get banned quickly.
  - Go to a subreddit like r/learnprogramming, r/starterpack, etc. and comment on people's posts to gain karma. Last time we checked, you need 5 karma to remove the reCaptcha feature from the direct messaging feature, which allows automated DM-ing.
  - Once you have 5 karma, the DM feature should be reCaptcha-free and you can start DM-ing.
  
Repeat as many times as needed, and try to make the Google Form surveys as simple and short as possible (5-6 short answer questions work best)!
