# Web Scrapping



# AIM of the project

* To Extract a list of cottages in France from a popular website using WebScraping technique and
  saving it in **CSV** format.
* The imformation we are extracting are as follows:
    * Name of the cottage
    * The price, 
    * Number of bedroom
    * Sleeps
    * Rating of the cottages.
* website:- https://www.holidayfrancedirect.co.uk/cottages-holidays/index.htm

# What is Web Scraping?
WebScraping is the technique from which we can extract data from webpage in automatic by sending a requests to that website.
The data we will get is unstructured data with html content and for cleaning that data we can use BeautifulSoup library.
there are other ways we can use 
Some of the main use case of Webscrapping is Price monitoring, News Gathering,  

## Work Flow
* Make requests to the website using get() method from the requests library.
* We will use html parser to parse the Html content.
* Extract name, price, bedrooms, sleeps and rating of all the cottage from single webpage.
* Then we will Paginate through all of the webpages and extract all the required information from each page.
* [Then will save the data in csv format by using pandas library.](https://github.com/Mhtag/webscrapping_project/blob/main/holiday_homes.csv).

# UseCase
    * Giving information to potential clients of various cottages, who are planning for holidays.
    * Provide information to a new Buisness owner who is looking to get into the field of tourism.
    
# Limitation of WebScraping
    * Prior to Scraping website we should check if a website allows to be scrape or not by using **/robots.txt**,
    suppose if we want to look at google if it allows it to be scraped or not then we will use **www.google.com/robots.txt**.
    * Another limitation is that if you provide to much requests at bulk, then website might get slow and the website admin might
    block your IP address from acessing the website.
    

### Libraries Used

* [Requests](https://docs.python-requests.org/en/v0.8.2/)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Pandas](https://pandas.pydata.org/docs/index.html)



