# End-of-end-ML-Project

This project carries on what we have undertaken for the ETL-Pipeline-for-Web-scraping project, which was to automate a process that extracts the following three different data sources by collecting match and tournament data along with information for players by web scraping ATP tours website, player names and a specific tournament name from Twitter using hashtags, and the popularity of players playing a specific match/game by scraping betting data from
Bet365(http://www.bet365.com/).

The project started from reading all the web scraped data sources that are stored in S3 bucket, processed the data, built, trained and deployed our machine learning model on SageMaker, then built an API taking HTTP POST requests using Lambda function and API gateway

