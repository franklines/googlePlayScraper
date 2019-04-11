## Google Play Python Scraper :snake:
---
A python script that I created to practice my web scraping skills. :) It utilizes the BeautifulSoup, requests, argsparse, re, and json libraries. Feel free to modify as you wish.

#### Help:
```bash
[~] python3 scraper.py -h
usage: scraper.py [-h] -b BUNDLEID

Process command line arguments

optional arguments:
  -h, --help            show this help message and exit

required arguments:
  -b BUNDLEID, --bundleid BUNDLEID
                        The bundle id of the app you wish to pull.
```


#### Example Usage:
```bash
[~] python3 scraper.py -b com.facebook.katana
{
 "name": "Facebook",
 "cover art": "https://lh3.googleusercontent.com/ZZPdzvlpK9r_Df9C3M7j1rNRi7hhHRvPhlklJ3lfi5jk86Jd1s0Y5wcQ1QgbVaAP5Q=s180",
 "description": "Keeping up with friends is faster and easier than ever. Share updates and photos, engage with friends and Pages, and stay connected to communities important to you. \n\nFeatures on the Facebook app include:\n\n* Connect with friends and family and meet new people on your social media network\n* Set status updates & use Facebook emoji to help relay what\u2019s going on in your world\n* Share photos, videos, and your favorite memories.\n* Get notifications when friends like and comment on your posts\n* Find local social events, and make plans to meet up with friends\n* Play games with any of your Facebook friends\n* Backup photos by saving them in albums\n* Follow your favorite artists, websites, and companies to get their latest news\n* Look up local businesses to see reviews, operation hours, and pictures\n* Buy and sell locally on Facebook Marketplace\n* Watch live videos on the go\n\n\nThe Facebook app does more than help you stay connected with your friends and interests. It's also your personal organizer for storing, saving and sharing photos. It's easy to share photos straight from your Android camera, and you have full control over your photos and privacy settings. You can choose when to keep individual photos private or even set up a secret photo album to control who sees it.\n\nFacebook also helps you keep up with the latest news and current events around the world. Subscribe to your favorite celebrities, brands, news sources, artists, or sports teams to follow their newsfeeds, watch live streaming videos and be caught up on the latest happenings no matter where you are!\n\nThe most important desktop features of Facebook are also available on the app, such as writing on timelines, liking photos, browsing for people, and editing your profile and groups. \n\nNow you can get early access to the next version of Facebook for Android by becoming a beta tester. Learn how to sign up, give feedback and leave the program in our Help Center: http://on.fb.me/133NwuP \n\nSign up directly here: \nhttp://play.google.com/apps/testing/com.facebook.katana\n\nProblems downloading or installing the app? See http://bit.ly/GPDownload1\nStill need help? Please tell us more about the issue. http://bit.ly/invalidpackage\n\nFacebook is only available for users age 13 and over.\nTerms of Service: http://m.facebook.com/terms.php.\n",
 "version": "Varies with device",
 "updated": "April 8, 2019"
}
```
