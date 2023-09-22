# Haskell Text Generator

## Overview

This project challenges your Haskell skills by requiring the implementation of an algorithmic automatic text generator. The generator learns statistics from a collection of documents and utilizes this knowledge to generate text based on user input.

## Project Implementation

- The project should be implemented in Haskell (Hugs98)

## Project Details

The project requires the implementation of a simple algorithmic automatic text generator that learns statistics from a collection of given documents and generates text based on these statistics. Here's an example:

```generateText "the man" 3 ```

Expected Output:

``` "the man saw the saw"  ```


## Implementation Functions

To implement the text generator, you need to implement the following functions:

- **wordToken**: Splits text into separate words and punctuation items.
- **wordTokenList**: Generates tokens (separated words/punctuation) from a list of texts.
- **uniqueBigrams**: Generates unique pairs of consecutive items in a list.
- **uniqueTrigrams**: Generates unique triples of consecutive items in a list.
- **bigramsFreq**: Generates Bigram frequencies, counting consecutive word pairs.
- **trigramsFreq**: Generates Trigram frequencies, counting consecutive word triples.
- **getFreq**: Extracts the frequency of an item from a list of (item, frequency) pairs.
- **generateOneProb**: Calculates the probability of a word following two other words based on trigram and bigram frequencies.
- **genProbPairs**: Generates a list of probabilities for each trigram based on trigram and bigram frequencies.
- **generateNextWord**: Chooses the next word based on probabilities, considering a probability threshold and handling cases where no word satisfies the condition.
- **generateText**: Generates text based on starting words and a specified word count, considering the statistics.

## Getting Started

To begin working on this project:

1. Clone the repository to your local machine.

2. Install Haskell (Hugs98) if you haven't already.

3. Implement the required functions in your Haskell source file.

4. Make use of the provided DataFile.hs for testing and learning.
