
## Make your kindle4rss.com have an automated recurring push button press to send your articles to Kindle

#### What is this?
It clicks on button to deliver new content on your kindle. Iff you only need 25 articles an dont need any other pro features this will deliver your content by pressing the button

#### Instructions
* export variables for username and password using KINDLE4RSS_USER and KINDLE4RSS_PASSWORD for script to work
* have Python3 installed and pip3 installs of urllib and bs4 modules
* Add this script to your crontab like this to get all articles at 5AM every day:
  ```
  0 5 * * * python ~/git/kindle4rss/kindle4rss_push.py
  ```

**original Python2 ported code:** www.github.com/dcrystalj/kindle4rss