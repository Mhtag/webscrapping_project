# Web Scrapping

# AIM of the project

* To provide a list of cottages in France from a popular website in **CSV** format which includes:-
    * Name of the cottage
    * The price, 
    * Number of bedroom
    * Sleeps
    * Rating of the cottages.
* website:- https://www.holidayfrancedirect.co.uk/cottages-holidays/index.htm

## Work Flow

* Extract name, price, bedrooms, sleeps and rating of all the cottage from single webpage.
* Then we will Paginate through all of the webpages and extract all the required information from each page.
* [Then will save the data in csv format by using pandas library.](https://github.com/Mhtag/webscrapping_project/blob/main/holiday_homes.csv) - 
    
### Libraries Used

* [Requests](https://docs.python-requests.org/en/v0.8.2/)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Pandas](https://pandas.pydata.org/docs/index.html)



