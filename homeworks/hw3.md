Ben is a budding data scientist. He was tasked with scraping tweets and putting the tweets and the associated metadata in a file. Ben decided to store the scraped data in a [`csv`](https://en.wikipedia.org/wiki/Comma-separated_values) file.

Ideally the file should have had three columns per line. First for the username, the second for the text of the tweet, and the last column for the date of the tweet. 
For instance, here are two lines from the file:

```
@mark,This is my first tweet after the rebranding,2022-07-23
@roger,Finally, I can start tweeting!,2023-01-11
```

The first line was formatted how Ben had expected. But since tweets can contain punctuation marks such as comma some lines (such as line 2 above) ended having more than three columns separated by comma.

Write a regular expression in Python that can match the text of the tweet on each line. 
Note that the tweet can contain numbers, hashtags, usernames and punctuation marks. 
