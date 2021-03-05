# Web Scraping

robots.txt

schema changes from web page to web page

>add User-Agent string of Firefox / Chrome (to show bot is a human)
>>headers = {"User-Agent":"Mozilla/5.0 (platform; rv:geckoversion) Gecko/geckotrail Firefox/firefoxversion"}

 #TYPES
1.  Scraping static pages\
		requests , BeautifulSoup
2.  Scraping interactive pages\
	Selenium\
	Layman’s term, selenium pretends to be a real user, it opens the browser, “moves” the cursor around and clicks buttons if you tell it to do so. The initial idea behind Selenium, as far as I know, is automated testing. However, Selenium is equally powerful when it comes to automating repetitive web-based tasks.
3.  Scraping images from Google