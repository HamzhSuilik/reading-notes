# Web Scrape with Python

 Web scraping : is data scraping used for extracting data from websites. The web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser

After fetching data from web pages, the data is arranged and analyzed and may be displayed to users in another location, saved in a database, or distributed to tables for analysis.

Web scraping is a technique to automatically access and extract large amounts of information from a website, which can save a huge amount of time and effort.

Some sites prohibit web scraping, so be sure to read the instructions for use of each site before you start scraping data so that your work is legal

we want to find the relevant pieces of code that contains our data , so the first thing that we need to do is to figure out where we can locate the links to the files we want to download inside the multiple levels of HTML tags

to see the raw code behind the site right click and click on “Inspect”. 

The next step is to search for links to text files with .txt extension, which are often be in the a tags .

Some python library for Web scraping
Requests , urllib.request , time , bs4

The next step is access the site with our requests library , using  the url to the website .
Then search for all a tags , then, extract the actual link that we want
