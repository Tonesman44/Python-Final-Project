# Python-Final-Project
Pokedex - The Temple University Reigion

## Steps to run the program
Note that you need python 3.5 or higher
python3 -m pip install RateMyProfessorAP
pip install -U Flask
pip3 install -U flask_cors
run app.py to start the local server with flask
run the HTML page
interact with the page and it will call the get command in the file to pull information from the Rate my professor API
Note that first 5 pictures on the website are examples and the search bar allows you to type in anyone from Temple's Rate my Prof database

### Demo
link to video - blank

### Challanges Faced - With Soulutions
Going into this project we had no experience with API's, HTML, or CSS. 
Right off the bat we decided to get the basic design of the website out of the way, so we found out how to write some basic HTML
From there we wanted to style the welcome page, so we learned some simple CSS to clean up the page and make it look nicer
Then we hit our first roadblock, the API
Here we had no idea where to start and Rate My Professor didn't have any help on their website.
So we traversed github and found an API from awhile back that a user named blank 
We then spent 3 days editing his code when we found out all we had to do was install the his API in the terminal
From there it was smoothe sailing, until we found out the API can only generate 8 teachers max per search because the website has a load more feature
In response to that, we pivoted and made a search bar on the website so you would focus on generating information for one teacher at a time
