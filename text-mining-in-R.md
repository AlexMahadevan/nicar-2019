## Text Mining in R With TidyText

<p>Using the tidyverse, let's analyze text</p>

Instead of list view, switch to grid view and it will tell you more abouteach dataframe, function, etc.

Twitter records everything in UTC, so need to convert to the timezone of the data.

Use regex to parse out things you don't need, like URLS, ambersands, etc.

unnest token = looks int the txt and splits it and makes a new row in the data for each piece of the split,copying it into other columns, define the tokwn, the simplest one is words and it just splits it into words.
* This turns everything into lowercase

anti-join 

Bigrams, combination of two words/phrases

sentiment analysis: the emotional content of words.
* Can be simple or complex, using a wide range of emtoions
* Look at some of the most common words and look for words that might have a different meaning in your context than how people areasked to rate the words
    * Gorge for the parks service
    * Trump versus trump
    * Include another column with whole text to find context
* Google has a natural language processing API, ook for other APIs
* "I certainly wouldnt bet my house on sentiment analysis"

Having done the unnest, the key bit of tidytext, from there on it's a whole lot of filtering and joining and dplyr 


