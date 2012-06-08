real-simple-sentiment
=====================

A javascript object that determines whether a set of sample text has either a positive or negative sentiment.

How does it work?
It compares each word of the sample text to a list of positive and negative words. Matches weight the text as positive or negative.

Is this accurate?
Reasonably? Part of being real simple is that it only looks at the words in the text not the grammar or structure of it. It also doesn't compare the frequency of words to their natural frequency to see if the text is using positive or negative words more than average, which might be good to add.
This project is more a learing exercise than anything else.

The set of positive and negative words that this object uses to weight the text is taken from word lists compiled by Bill McDonald, Professor of Finance at Norte Dame.
http://nd.edu/~mcdonald/Word_Lists.html