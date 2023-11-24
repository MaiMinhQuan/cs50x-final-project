# Multidisciplinary Quiz
#### Video Demo:  <https://www.youtube.com/watch?v=YZ_w6-M49Jc>
#### Description:
My program provides interesting questions about different areas of life to help users gain new knowledge about the world around us.

The "app.py" file uses "Flask" to control login, account registration and transitions between websites.

The "helpers.py" file installs a few functions that make installing "app.py" easier.

The file "project.db" installs the user's account database.

The file "requirements.txt" contains the names of the libraries that need to be installed.

The "flask_session" folder contains the "flask" library that helps us maintain user login during use.

The "templates" folder contains the html file that installs the website.

The "static" folder contains css files and background images of the website

In particular, the file "apology.html" shows errors when users use the website.

The file "homepage.html" appears on the website's homepage after logging in.

The file "layout.html" is the general layout of the website's html files.

The file "login.html" is the login interface of the website.

The file "register.html" is the account registration interface of the website.

Files "sea.html", "universe.html", "plant.html" contain questions on different topics.

First of all, users must register for an account and log in to the website. If users do not enter username or password or confirmaton, apology notification will show up. If password does not match confirmation, the registration will fail. if username already exists in the database, the registration will also fail. When loggin in accounts, if username does not exsit or the password is not correct, the login wil fail.

After that, users are taken to the homepage of the website, where users can choose questions on different topics.There are three topics available which are: Sea, Universe, Plant. In the sea topic, users can learn more about the ocean, the ceature under the sea, the coral, ...In the universe topic, users can learn more about basic concept of the space, some basic definitions, ...In the plant topic, users can learn more about interesting kinds of plants, some mind-blowing facts, some application of plants on our daily lives, ... If the user chooses the correct answer, the answer will appear in green, otherwise it will appear in red. When completing the questions, the website will display users' results. Users can start over to improve their score.

At the end, users can log out of their accounts.

And that is it.Thank you very much CS50x.

That was CS50.