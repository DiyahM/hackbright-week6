#Hackbright Front-end Development Week 6

##Exercises

###Code Appetizer
1. Create a new html page using the html provided on the next slide.
2. Add a button that displays the text ‘More’ to the bottom of the page
3. Add the following functionality to the page: ‘When a user clicks the More button, the next 5 results are displayed on the page’

###Exercise 1
1. Create a single html page that has the below features:
2. User can search google books by subject (hint: you’ll need to create a search form -- use only an input element and button element)
3. Use $.get method and pass q, startIndex, and maxResults into second attribute $.get(“https://www.googleapis.com/books/v1/volumes”, {q: <searchterm>, startIndex: <start>, maxResults: <num-of-results>}, function(data){ <do something here> });
4. Display the title, author, book image for each book in the search results.
5. Initially only return a max of 20 results.
6. User clicks the more button to display the next 20. (hint: use the pagination feature of the api)
7. Bonus: Make it look PRETTY!

