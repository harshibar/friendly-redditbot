# my_friendly_bot
a wholesome reddit bot

## 5 things to remember when making your bot
### 1. Read the Reddit [Bottiquete](https://www.reddit.com/wiki/bottiquette)!
There are lots of restrictions on Reddit Bots, so read the Reddit Bottiquete when planning your project. Essentially, make sure your bot is useful, and does not spam or comment when it is not invoked.

### 2. Target specific subreddits that would benefit the most from your bot.
To prevent your bot from being banned, allow it to only function in specific subreddits. Lots of times, bots are banned because they are spamming communities or are being invoked out-of-context. Limiting functionality to certain communities can prevent this from happening.


### 3. Make a separate Reddit account for your bot!
Reddit bots are registered as 'scripts' running under a Reddit user account. So, when setting up your `config.py` file, first create a new Reddit account, and use those credentials. Also, remember not to share or upload the `config.py` file on Github!

### 4. Use pushshift.io to collect Reddit data.
If you want to scan all of reddit, using just PRAW can be very slow. Luckily, [pushshift.io](http://pushshift.io) has a  [clean API](https://github.com/pushshift/api) that allows you to search all of Reddit. Use the `after` keyword in the query to find results from after the last time the bot was invoked so the query runs quickly!

### 5. You can automate the bot using Heroku!
This is something I didn't do in my project, but I did set up the `Procfile` to make connecting to Heroku even easier. [Here](https://github.com/kylelobo/Reddit-Bot#after_setting_up_repo_on_heroku) are some instructions on how to set up the bot on Heroku servers!

## Other cool bots
1. [u/Fact-Check-Bot](https://www.reddit.com/user/Fact-Check-Bot)
2. [u/autowikibot](http://www.reddit.com/user/autowikibot) - This bot has been retired, but I'm thinking of reviving it!

## How to use this bot
As of now, on any subreddit, comment one of the following messages, and my_friendly_bot will reply (within the same day because I'm running this manually):
1. i'm sad, my_friendly_bot
2. i'm bored, my_friendly_bot
3. i'm lonely, my_friendly_bot
4. i'm single, my_friendly_bot
5. i'm smart, my_friendly_bot
