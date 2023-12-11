# PSL_Project4
This code implement a movie recommender system and gives the user two types of recommender systems. 
System I: Recommendation Based on Genres & System II: Recommendation Based on IBCF (recommendation based on what movies the user rated)

To run the flask app enter the following commands in the terminal
set FLASK_APP=app.py
set FLASK_ENV=development
flask run
In the terminal, it should show which port the application is running on, navigate to that url on your browser
 Example "Running on http://127.0.0.1:5000 (Press CTRL+C to quit)"

Files:
    project4Python 
        - contains the python code to implement system I and System II
    project4R 
        - contains the R code to get the cosine similarity matrix to use in project4Python System II
    psl_project4_narjum 
        - pdf of the HTML files of R and python code
    app.py 
        - Contains the methods for getting movies for System I & System II
         - It includes the IBCF method, getting movies based on genere, getting popular movies etc.
    static folder
        - contains the JS files to popluate the HTML page 
        - conatins styles.css used to add styling the HTML page
    templates folder
        - contains the HTML file