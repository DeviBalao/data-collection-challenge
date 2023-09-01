# data-collection-challenge

#### Pre-requisites:
The following libraries are required for this challenge and can be installed using the following commands in the appropriate environment (E.g dev):

    pip install "splinter[selenium4]"
    
    pip install bs4
    
    pip install html5lib
    
    pip install lxml

##### chromedriver installation:
•	Get the appropriate version of chromedriver from the following link: https://chromedriver.chromium.org/downloads

•	Extract the files to c:\users folder and set the environment variable path (use New and browse the folder location to set the path).

![image](https://github.com/TestUser-2022/data-collection-challenge/assets/98562722/e6b30488-313b-4f75-b606-a57838a25fe0)

•	Execute the following command in the appropriate environment:

      o	pip install chromedriver-autoinstaller

•	In the command prompt in the appropriate environment and in the folder path in which the file exists - execute “chromedriver” to verify it gets started successfully.

<img width="851" alt="image" src="https://github.com/TestUser-2022/data-collection-challenge/assets/98562722/5a932a91-1f78-44fe-80cd-d86135e20e18">

<img width="659" alt="image" src="https://github.com/TestUser-2022/data-collection-challenge/assets/98562722/d71c0092-7253-42ff-a279-66d30673e558">

After installing chromedriver, do a complete restart/refresh of the environment in VScode.


This challenge has two technical deliverables:
-
•	Part 1: Scrape titles and preview text from Mars news articles.

•	Part 2: Scrape and analyze Mars weather data, which exists in a table.

### Part 1: Scrape Titles and Preview Text from Mars News:
##### File - part_1_mars_news.ipynb

•	Use automated browsing to visit the Mars news site - https://static.bc-edx.com/data/web/mars_news/index.html

•	Create a Beautiful Soup object and use it to extract text elements from the website.

•	Extract the titles and preview text of the news articles.

•	Store the scraping results in Python data structures and print the results.


### Part 2: Scrape and Analyze Mars Weather Data:
##### File - part_2_mars_weather.ipynb

•	Use automated browsing to visit the Mars weather site - https://static.bc-edx.com/data/web/mars_facts/temperature.html

•	Create a Beautiful Soup object and use it to extract the data from HTML table.

•	Prepare the data, analyze the data, plot graphs.

•	Save the data to a csv file (mars_data.csv) in data folder.
