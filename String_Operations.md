# String Operations and Slicing Worksheet

**shelley** = """The being finished speaking and fixed his looks upon me in the expectation of a reply. But I was bewildered, perplexed,

and unable to arrange my ideas sufficiently to understand the full extent of his proposition.         """


**austen** = """It is a truth universally acknowledged, that a single man in possession of a good fortune, must be in want of a wife.

However little known the feelings or views of such a man may be on his first entering a neighbourhood, this truth is so well fixed in the minds of the surrounding families, that he is considered as the rightful property of some one or other of their daughters."""

## Operations

.capitalize()
.center(width)
.count(sub)
.find(sub)
.rfind(sub)
.join(list)
.ljust(width)
.rjust(width)
.lower()
.lstrip()
.rstrip()
.replace(oldsub, newsub)
.split()
.title()
.upper()


## Slicing

1. Pull out the phrase "The being" from shelley.
2. Pull out the phrase "universally acknowledged" from austen.
3. Combine these two phrases.

Using the .split function, split shelley into indivdiual words. Starting with the second word, use slicing to pull out every other word.

# Explain the output

a) for word in "One can never have enough socks.".split():
      print(word + "...")
b) word = "lemon pies"
   for letter in word.split("e"):
      print(letter)
