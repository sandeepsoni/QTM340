[Zipf's law](https://en.wikipedia.org/wiki/Zipf%27s_law) is an empirical law in linguistics that 
explains the statistical relationship between the rank of the word (when sorted by frequency) and the frequency. 
In particular the rank of the word is inversely proportional to its frequency. 
Visually, Zipf's law can be demostrated by a plotting the log rank against the log frequency of a word; 
one can verify that for a sufficiently large size of the text corpus, the plot will look like a straight line.

Suppose we have a large document, say 10 million word tokens in total, on which we have validated Zipf's law. 
The document is segmented into words and indexed using integers such that the first word has index 0.

Answer the following questions as either True or False. Give a short explanation (1-3 sentences) for your answer.

1. If we pick words from index positions that are multiples of 10 (e.g., 10th token, 20th token, 30th token, and so on) and create a count distribution of the selected words, the word rank and their frequency will follow Zipf's law.
2. If we randomly drop a contiguous segment of words, say between positions 435987 to 1328546, the word rank and their frequency for the remaining words will still follow Zipf's law    
