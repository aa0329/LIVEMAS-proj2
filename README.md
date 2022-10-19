# Analysis of Climate Change Sentiment in 2022

## SRC
### Installing / Building the Code
To install the code, download the RMD file in the SRC folder. Open this in RStudio and run the code. All of the libraries that need to be installed are already included at the top of the file, so the code solely needs to be ran to successfully build the code. 

### Code Usage
This code can be used to understand different attitudes towards climate change. 

## DATA
Our data was obtained from Kaggle [here](https://www.kaggle.com/datasets/die9origephit/climate-change-tweets).
### Data Dictionary
| Column  | Description | Potential Values |
| ------ |  ----------- | ----------------
| Timestamp  | Indicates the date and time that the tweet was published | Any time/date between 01/17/2022-07/19/2022. |
| Embedded Text  | The contents of the tweet that relate to climate change | A string of texts with <= 280 characters. |
| Likes | The amount of likes that the tweet received  | Any integer from 1-9450. |
| Retweets |  The amount of retweets that the tweet received | Any integer value from 1-20.6K |
| Popularity |  Based on the number of likes, determines how popular the tweets are  |Score from 1-5, 1 being the least popular |

## FIGURES
| Figure Number | Figure Name | Key Takeaways |
| ----------- | ------ |  ----------- |
Figure 1 | Number of Tweets per Popularity Level | The majority of tweets lie in popularity level 1
Figure 2 | Number of Tweets per Month | July saw the most Tweets about climate change
Figure 3 | Climate Change AFINN Sentiment Range | The sentiment is skewed negative
Figure 4 | Frequency per NRC Sentiment Category | Other than positive and negative, the most common emotion was fear
Figure 5 | Frequency per Bing Sentiment Category | The majority of tweets were classified as having negative sentiment

## REFERENCES
[Milestone 1: Creating a Hypothesis](https://docs.google.com/document/d/1iab8vQS97yk5T3rzESs86RILw8knzaKODZ6kapU4sMc/edit?usp=sharing)

[Milestone 2: Exploratory Data Analysis & Analysis Plan](https://docs.google.com/document/d/1Y3M5PIjCS9c8360Ezs0bDVY6BEs92JIG1a5HZvdqsrY/edit?usp=sharing)

[1] United Nations, “What is climate change?,” United Nations. [Online]. Available: https://www.un.org/en/climatechange/what-is-climate-change. [Accessed: 05-Oct-2022]. 

[2] “United in Science: We are Heading in the Wrong Direction,” Unfccc.int. [Online]. Available: https://unfccc.int/news/united-in-science-we-are-heading-in-the-wrong-direction. [Accessed: 05-Oct-2022]. 

[3] M. Jaganmohan, “Climate change as a threat 2020,” Statista, 05-May-2022. [Online]. Available: https://www.statista.com/statistics/1305680/climate-emergency-public-awareness/. [Accessed: 05-Oct-2022]. 

[4] M. Jaganmohan, “Climate change as a threat 2020,” Statista, 05-May-2022. [Online]. Available: https://www.statista.com/statistics/1305680/climate-emergency-public-awareness/. [Accessed: 05-Oct-2022]. 

[5] “Twitter sentiment analysis using Python,” GeeksforGeeks, 28-Jun-2022. [Online]. Available: https://www.geeksforgeeks.org/twitter-sentiment-analysis-using-python/. [Accessed: 12-Oct-2022]. 
