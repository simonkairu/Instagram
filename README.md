# Instagram

#### 4/12/2021  

#### By **Simon Kairu**  

## Description  
 Instagram is an app where users are aple to create an account and upload images.Viewers are able to like comment and share. 

  |

## Features   
*As a user of Instagram web application, you will be able to:  
*Sign in to the application to start using.
*Upload my pictures to the application.
*See my profile with all my pictures.
*Follow other users and see their pictures on my timeline.
*Like a picture and leave a comment on it.

  ## Setup/Installation Requirements  
 ### To interact with the Instagram web application:   
* Have the latest version of browser installed  
* Click on this <a href = "https://gram254.herokuapp.com/">link</a> to view the instagram. 
 
 ### To contribute to Instagram web application:  
 #### Clone the Repo  
 * Create an account on Github
* Fork the repository from Github with this <a href = "https://github.com/simonkairu/Instagram.git" >link </a>
* Clone the repository
* Open the project cloned project

####  Activate virtual environment
Activate virtual environment using python3.6 as default handler
    `virtualenv -p /usr/bin/python3.6 venv && source venv/bin/activate`

####  Install dependancies
Install dependancies that will create an environment for the app to run `pip3 install -r requirements.txt`   

####  Create the Database
    - psql
    - CREATE DATABASE gram;

####  .env file
Create .env file and paste paste the following filling where appropriate:

    SECRET_KEY = '<Secret_key>'
    DBNAME = 'gram'
    USER = '<Username>'
    PASSWORD = '<password>'
    DEBUG = True  

#### Run initial Migration
    python3.8 manage.py makemigrations Instagram
    python3.8 manage.py migrate     

#### Run the app
    python3.8 manage.py runserver
    Open terminal on localhost:8000    

## Known Bugs
There are no known bugs so far  

## Technologies Used  
* Python v3.8  
* HTML
* Bootstrap
* Django  
* Postgres  

## Support and contact details
In case of any problem while interacting with the web application, reach out to me at simon.mureithi@student.moringaschool.com

### License.
MIT Copyright (c) 2021 **[MITlicense](LICENSE)**