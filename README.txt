This repository aims to instruct users on scraping data from the popular subreddit, r/wallstreetbets.

ETL instructions are as follows:
1) Register Reddit API Key and populate 'reddit_keys' file with credentials
2) Run 'First_Run_hot'
  a) I use this file to pull by "hot" posts, but it can easily be changed to pull by "new", "top", etc.
3) After Running Step 2, run "Operational_Run_hot"
  a) The timer to pull from the API is expressed in seconds
    i) First timer is currently set to 5 minutes (600 sec)
    ii) The operational sleep timer is currently set to 24 hours (86400 sec)
