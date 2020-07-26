# Web-Scraping
Scrape data from a website using BeautifulSoup.
!(https://github.com/abhiecnsit/Web-Scraping/blob/master/Website%20Scrapping.png)
## Task
We have to get the Session Average Value of DDR4 4G(512M*8) 2400 Mbps(Marked in red rectangle) from [DRAMeXchang](https://www.dramexchange.com/) website.

To get the desired value we will use Selenium WebDriver and BeautifulSoup.
## Prerequisite
You should have the following libraries installed:
- Pandas
- Selenium
- requests
- BeautifulSoup (bs4)

Also, please install webdriver of your web browser(Chrome, Firefox, etc.)
Before going through the codes please read about Selenium Webdriver and BeautifulSoup for better understanding.

## Steps:
1. Create a connection with the website using webdriver.
2. Get all the website content using BeautifulSoup.
3. Get the table data.
4. From table data sort-out column names('Item' and 'Session Average').
5. Go through each row and look for the desired row in Item column(DDR4 4G(512M*8) 2400 Mbps) and get the required value.
            or
4. Collect the entire table data and convert it into a pandas DataFrame.
5. Get the required value by indexing the DataFrame.

