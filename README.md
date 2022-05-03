# Scraping-TripAdvisor-Reviews-using-Selenium
This project aims to scrape reviews by hotel guests from TripAdvisor for ROW NYC Hotel in New York City. A total of 9040 reviews were scraped. The review date, review title, review and ratings were extracted using Selenium. The extracted data is then packed into a pandas dataframe and exported to CSV for ready usage in NLP projects. You may access the CSV file named 'Reviews TA'. 

The code can also be adjusted to scrape as many pages of reviews as you may need. 

## Why the use of Selenium instead of Beautiful Soup?
The first choice of web scraper for this project is Beautiful Soup. However, there were some challenges in getting requests from the URL and hence, the Selenium was used instead. 

## The potential use of this dataset:
1. Sentiment Analysis using Machine Learning
2. Topic Modeling to get an sense of the topics that the hotel guests are concerned about
3. Transfer learning using BERT can also be used for this dataset 

## Libraries needed
1. time
2. pandas
3. selenium 
4. webdriver_manager.chrome 
