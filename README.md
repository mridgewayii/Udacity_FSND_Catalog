# Udacity_FSND_Catalog
Udacity FSND Catalog Project
# Program Description
This program is to fulfill the requirements of the Udacity FSND Web Server Catalog Project.  This program creates a sqlite database object that stores movie titles, categories, descriptions and stars under two different tables.  There is also a table for users.  The application employees the Google oauth2 user authentication API and restricts editing to only those users logged in.  Category items are also restricting to editing by the authenticated user that added the item originally. 
# Requirements
1. Python 2.7
2. The website is built around the Bootstrap 3.3.7 and JQuery 2.1.4 frameworks and uses CDNs for obtaining the required files on page loading. Access to this CDN outside of any firewalls is required to properly display the pages.
3. The webserver that will run this program will need to have the following Python packages loaded for the application to run:
  A. Flask
  B. sqlalchemy
  C. oauth2client.client
  
  These are not installed with the base Python package and instructions for installing each are located on the package's website and vary depending on your opperating system.
 # Acknowledgements
 A significant portion of this program is either a direct representation or a modification of the lectures in the Udacity FSND program.  This includes but is not limited to the Google Signin functions, the functions to render database queries, and the general formatting of the html templates.  Similarities can be seen with the Udacity "Resturants Application" completed as part of this course.
 # How to Run Program
 1. Unzip the package into your prefered webserver directory.
 2. Execute the database_setup.py file to create the sqlite database
 3. Execute the database_load.py file to fill the new sqlite database with some data.
 4. Execute the main.py program file to initiate the program
 5. Use a internet browser of your choice and navigate to localhost:8000
 6. Use the Login button at the top right of the screen to authenticate with Google oauth2 API
 7. View, add, and create additional item entries in the catalog.
 # License
 1. Python is used under the MIT license
