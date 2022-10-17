# TwitterAnalysis

For this assignment, I have incorporated sentiment analysis on twitter for the use case of comparing Tweets during elections, to know about the people's opinion on the running candidates!

## My Program:
### Functions:
> get_tweets()
  >> Retrieves tweet based on a keyword

> preprocess_tweet()
  >> Cleans text data up, leaving only 2 or more char long non-stepwords composed of A-Z & a-z only in lowercase

> clean_tweet()
  >> Gives the dataframe of the cleaned tweets

> sentiment()
  >> Takes dataframe as input, does sentiment analysis based on Text Blob and gives out whether the tweet is negative, positive, negative or neutral.

![image](https://user-images.githubusercontent.com/113374250/196083987-84326bbd-75dd-4f16-969c-3379bca60f14.png)

  
> count_values_in_column()
  >> Retrieves the number of tweets for positive, negative and neutral sentiment.

![image](https://user-images.githubusercontent.com/113374250/196084127-2e5bd315-f9be-4460-8cf4-eb73b419146e.png)

### Use Case
I have used the twitter api and text blob sentiment analysis to compare the opinion between joe biden and donald trump among twitter users.

### Output
![image](https://user-images.githubusercontent.com/113374250/196084441-90c625eb-9eae-469c-8985-8a821c75849e.png)


