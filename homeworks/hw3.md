Ben is a budding data scientist. He was tasked to scraping tweets and putting the tweets and the metadata in a file. 
Ben decided to store the data in a [`csv`](https://en.wikipedia.org/wiki/Comma-separated_values) file.

Ideally the file should have had three columns per line for the username, the tweet, and the date of the tweet. 
For instance, here are a two lines from the file:

```
@mark,This is my first tweet after the rebranding,2022-07-23
@roger,Finally, I can start tweeting,2023-01-11
```

Since tweets can contain punctuation marks such as comma some lines contain more than three columns separated by comma.

Write a regular expression in Python that can match the text of the tweet on each line. 
Note that the tweet can contain numbers, hashtags, usernames. 
