### ENGO 551 Lab 0
### Kevin Liu
### 30069547 
------------------
#### ENGO 551 - Adv. Topics on Geospatial Technologies
-------------------
This project is a book review webiste where users can search for books. Users will be able to register for on the website and then log in using their username and password. Once they log in, they will be able to search for books, leave reviews for individual books, and see the reviews made by other people. I also use a third-party API by Google Books, another book review website, to pull in ratings from a broader audience. Finally, users will be able to query for book details and book reviews programmatically via my website’s API. 

# Files

### book.html
This file displays details about a single book

### booksearch.html
This file allows the user to search for books by either isbn, publication year, author, or title.

### bookslist.html
This file displays all the books that matches what the user searched for.

### error.html
This file displays an error when something goes wrong. 

### index.html
This file is the first page of my webpage and is also where users registrate for the website.

### layout.html
This file is the base layout for each page of my web application. Each html page inherits from this.

### loginform.html
This file displays the login form where the users login to the website.

### reviews.html
This file was supposed show the user that they have successfully submitted a review for the book, but I decided to not use it.

### success.html
This file tells the user that they have successfully registrated for my website.

### application.py 
This is where the python code is written and is the main file for this flask application.

