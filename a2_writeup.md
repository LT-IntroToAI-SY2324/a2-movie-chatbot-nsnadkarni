# Assignment 2 - Write UP

## Description
This assignment is about learning and applying the while loop and iterating through multiple lists at a time.  We also will discuss how we match things in chatbots in order to extract what a user is trying to find.  Next assignment we will work with data bases and how we can extract information from them.

## What to complete
1. Go through the notes.py file w/ Mr. Berg
2. Complete `a2.py`, Mr. Berg will walk everyone through the process
3. Make sure you pass all asserts in `a2.py`
4. Complete the reflection problems below
5. Push your code to github for grading

## Reflection Questions
1. What was difficult for you while completing the match function?

Making sure the index didn’t go out of bounds for the “%” part of the match function was tricky, but it ended up just being a line of code that I tabbed one too many times, so instead of adding to the index after the loop ended, it would just keep adding to the index within the loop. Also I had an extra space at the end when returning, but after I realised you could splice strings, I just added [:-1] and it fixed it. Other than those things, nothing else was difficult.

2. Explain how you could use the match function for extracting information from a movie database.

We could use the match function to look for certain words using “_” and we could look for movie titles, actors etc, using “%”. For example, we could have [“Who”, “acted”, “in”, “the”, “movie”, “shawshank”, “redemption”] and we can use the pattern [“Who”, “%”, “the”, “movie”, “%”], then have an if statement for “acted in” and pass into the database, “shawshank redemption” and find the actors (since we are in the acted in if statement) and print those actors.


