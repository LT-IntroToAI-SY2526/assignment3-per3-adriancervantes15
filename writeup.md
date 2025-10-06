# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
One key programming technique that I learned while completing this assignment was that I could do compound inequalities in python as opposed to two seperate statements. I learned java last year so when a problem like this occurred I would use two seperate statements. Python's shortcuts are very useful.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
When a user types in a query, the code puts that query into a list. It then calls search_pa_list which loops through each pattern action pair, and calls match. In match certain words are returned. Then search_pa_list runs a function which will looks through movie_db and will return whatever the function gets. What the function returns is the answer to the query.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
One real world application for this type of pattern-matching chatbot system would be the chatbots used in websites. I think they are called virtual assistants. Although the chatbot we made and virtual assistants are used for different topics, they essentially do the same thing. Which is look for key words in your questions in order to give you a response.  
