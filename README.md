# NodeJS_Crawler

With this project i have different aims.

 1. Crawl one specific domains all urls.

 2. Find IoT words from this urls.

 3. Render this url with highlighting "IoT" words.


I crawled one domain's different urls, and i found urls which include "IoT" word then rendered scraped page as highlighted "IOT".

crawled domain : https://www.chevron.com

searched keyword : IoT

Found one page which contain IoT word from 1057 different pages. But you can change domain names and keywords, then using my script you can find your keywords included pages up to 10 urls.

# When i started to this project

I didnt know to how crawl and scrape web pages using nodeJS, But many times i scraped and crawled web pages using python and frame works. So i know what should i do and i can predict what will i strugle.

First of all crawling and scraping many times think as same process but crawl and scrape different things. For example while crawling web pages you encounter with blocking and you should use user agents. I used different user agent for every request. With this way i couldnt blocked. By the way for catching blocking  i used http status codes logging. If many 403 error codes comes consequtively, i realized that i am blocked. For this reason i used user agents.
