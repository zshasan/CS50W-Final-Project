MAIN
----
    My Django project is a kids math game site consisting of four games(Addition, Subtraction, Multiplication and Divison).  There is also a Journal-like option that allows the user to record their scores or thoughts when they
please.

DISTINCTIVENESS AND COMPLEXITY
------------------------------
    I believe my project satsifies the distinctiveness and complexity requirements because of the following reasons:
        - My project is not a clone of any of the projects done throughout the course and has a significant amount of distinctiveness
        - The part that is similiar to something in the course was the React addition game taught in week 6.  The difference between that game and the games in my project, is that my games are more complex.  In the lecture
          the game took over the whole page and kept diaplying questions until the user got 10 correct answers and ended there.  In my project there are four different games and each of them tracks how many questions the user
          got correct/incorrect.  When the user reaches either 10 correct or 10 incorrect answers the user is lead to a victory/loss screen.  This then allows the user to return to the main menu and play again
        - The complexity is further by the use of React for the games and the use of Javascript for hiding login information on the Profile page.
        - Another feature that adds complexity is the Journal/Log feature.  This feature is accessed from the Profile page.  It allows the user to edit and post a log post of whatever they please(including their scores and
          victories/losses everytime they play).  It also records the time and date of updated post
        - I also used unique CSS for the look of the project

WHAT’S CONTAINED IN EACH FILE
-----------------------------
    'migrations' folder:  Contains the file created after migrations when changes were made to the models.py file
    'static' folder:  Contains the defunct js files, the image folder which contains the project's background image and the main CSS file for the entire project
    'templates' folder:  Contains all the html files.
        - add.html, subtract.html, multiply.html and divide.html:  The html pages for each of the 4 games.  Coded in HTML5 and React
        - index, layout, login and register:  The base html pages.  layout.html sets us the navigation abd base for the entire project, with the rest extending from it.  index.html is the main page.  login.html and
          register.html are the pages for user login and user registration
        - profile, post_detail and post_edit:  profile.html is the base where the user can edit their log post and where they can view their username, password and email address(all 3 with the ability to be hidden
          through a toggle coded by javascript).  post_detail.html is the file that allows what was save in the post onto the profile.html page(this includes the title and the date the post of updated).
          post_edit.html is the file that allows the user to edit the post and its title which is then saved with a button near the bottom

HOW TO RUN
----------
    1) cd ~/cs50web/FinalProject/Final(For my device, ignore otherwise)
    2) python manage.py runserver 0.0.0.0:8080
    3) Open in new page
    4) Go to https://ide-c0b85ec7a3fd4812af821235a93b7f16-8080.cs50.ws/
    5) Enjoy!

ADDITIONAL INFORMATION
----------------------
    Please ignore the .js filesin the 'static' folder and the node_modules folder.  Those became obslete later during development.
