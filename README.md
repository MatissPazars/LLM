# LLM
Making my own LLM



## Markov Chain.

Before we get to the later really juicy things, we must first start small - really humble with a simple Markov chain. What it is is really simple: just follow each word by statistically the most likely word to follow it with. e.g. - if you scraped the internet, looking for what word most often follows the word *united*, then one of the most common would be *states*. why? Because that specific word combination has meaning - its the name of a well-known nation. Thus statistically - its really easy to bet that after the word united, the word states will be next. and this is the whole idea of markov chains - just map statistically what word follows what word, with zero outside context. For example in my database, the word *the* is most often (1.7% of the time) followed by the word *first*. and thus what the whole AI does is just continues the line by outputting the most statistically frequent word to follow the prior one. it does NOT take actual context or surroundings into consideration and is not capable of any actual perception, thought or anything but its the first step. 

