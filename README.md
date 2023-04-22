# Freelance beauticians


![responsiviness](./readme_docs/)


# About


Live Site: [💻](https://pp4-beautysalon.herokuapp.com/)
---
<br>

This is a website to show Profiles of freelance hairstylist and beauticians. The main purpose of the site is to allow users to browse and view profiles whether they are registered or not. Registered users can add, update and delete their own profiles on the app and can leave review to other user profiles. 

<br>

# UX

## Target Users
---
User who can create a Profile and write about their profession and work availability as a freelance stylist or beautician.

### Unregistered user

Unregistered user who can find freelance or mobile stylist/beauticians to work for their needs.

### Registered user

Users who can showcase their work to let others know their area of expertise and available places


### Agile

Agile methodology in GitHub was used to create this website.  User Stories were created using issues on git hub.
The link to the project board can be found [here](https://github.com/users/MinuMThomas/projects/10)


### User Stories

HomePage **as an unregistered user**

- As a user I want to be able to tell what the website is about.
- As a user I want to see the profiles.
- As a user I want to Signup to the site. 
- As a user I want to leave a review.
   
Homepage <strong><u>(Logged in) </u></strong>
- As a user I want to be able to create my profile.
- As a user I want to edit my profile.
- As a user I want to delete my profile.


##Register

- As a user I want to be able to Signup.

##Login Page

- As a user I want to be able to login with username and password.


##Logout Page

- As a user I want to be able to logout.
 

## User Stories - create profile

  - create profile form: name, profession, place, email,bio, avatar


### User Story: View Reviews

- As a registered User, I want to see  all the comments in the posts when I log in.
  
### User Story: Add Review

- As a registered User, I want to add  review .


### User Story: User Profile

- As a registered User, I want to view, edit, and delete my profile 


## Flowcharts



[flowchart](./readme_docs)




# Features

The list and screenshot about them can be found [here](readme_docs/).

# Features to Implement in Future

1. Login as user who can only add reviews.

2. Registered user who can create profile will                    
    showcase their work too as posting images 



# Bugs


# Design

The wireframes can be found [here]()

The details to the design can be found [here]()

# Technologies Used


## Languages

- [HTML](https://html.com/)

- [CSS](https://www.w3.org/Style/CSS/)

- [Python](https://www.python.org/)

- [JavaScript](https://www.javascript.com/)


## Frameworks and Libraries

- [Django](https://www.djangoproject.com/)
Documentation for [here](https://docs.djangoproject.com/en/4.1/intro/)

- [Jquery](https://jquery.com/) 

- [Boostrap](https://getbootstrap.com/)

- [Gunicorn](https://gunicorn.org/)

- [CkEditor](https://ckeditor.com/)


## Database Host

- [ElephantSQL](https://www.elephantsql.com/)  
   Documentation for set a database [here](https://www.elephantsql.com/docs/).


## Deployment Host

- [Heroku](https://id.heroku.com/login)


## Other Resources

- [GitHub](https://github.com/)

- [GitPod](https://www.gitpod.io/)

- [Allauth](https://django-allauth.readthedocs.io/)

- [DjangoCrispyForms](https://django-cryptography.readthedocs.io/)

- [Cloudinary Media](https://cloudinary.com/)

- [Summernote](https://summernote.org/)

- [GoogleFonts](https://fonts.google.com/knowledge)

- [FontAwesome](https://fontawesome.com/)


# Validation

The validation reports can be found [here](./readme_docs/)





## Responsiveness

The site had been test for the following devices:

Mobile:  

Tablet: 

computer :

The site had been test in Chrome seeming all according to the design. In Firefox, the animation for the regions in the index come out a bit out of shape but still fully functional. In Internet Explorer all seems to work as the design.

<br>

# Manual Testing


The following features are present in all the pages.


## Navbar


The features will be displayed according to the logged user, as marked in [features]


| Feature       | Expected Action       | Result    |
|---    |---    |---    |
| Logo          | Brings the user to the landing page |Pass|
| Toggle button | Toggle to reveal the menu           |Pass |
| Register      | Brings the user to the Sign Up page |Pass |
| Log In        | Brings the user to the Log In page  |Pass |
| My Profile    | Brings the user to view Profile page|Pass|
| Log Out       | Brings the users to  Sign Out page  |Pass|
| Admin Page    | Brings the user to the Admin Page   |Pass|     


## Messages


| Feature       | Expected Action       | Result    |
|---    |---    |---    |
| Messages  |displayed on the screen when an action happens. | Pass  |




## Footer


| Feature       | Expected Action       | Result    |
|---    |---    |---    |
| Facebook Icon | Opens facebook in a new tab.     | Pass   |
| Instagram Icon  | Opens instagram in a new tab.  | Pass   |





## Index Page view for unregistered users


| Feature       | Expected Action       | Result    |
|---    |---    |---    |
|view Profiles  | user can view Profiles              | Pass|
|detail view    |user can see individual profile      | Pass|
|review view    |user can see reviews in the profile  | Pass|
  


## Index Page view for registered users

| Feature       | Expected Action       | Result    |
|---    |---    |---    |
|view Profiles| user can view Profiles              |Pass |
|detail view    |user can see individual profile    | Pass|
|review view    |user can see reviews in the profile| Pass|
|add review     |user can add reviews in the profile| Pass|
|create profile |user can create profile            | Pass|


## Profile Detail Page


The features will be displayed according to the logged user,  . 

| Feature       | Expected Action       | Result    |
|---    |---    |---    |
|Review form    |the logged in users can to write review.     | Pass |
| submit review | Once submit button is clicked, it saved.    | Pass |
|               |and renders in the review card.              |      |


## Create Profile

This page is for registered users.

| Feature       | Expected Action       | Result    |
|---    |---    |---    |
|Link to form   |Opens a form where user can enter their information.    |Pass|
| user information form| Save and display in the page the information    |Pass|
|                      |that was entered once the submit button is clicked

If user does not enter their information there is a place holder image that will be displayed by default.



## My profile
 
This page will appear once user create the profile

| Feature       | Expected Action       | Result    |
|---    |---    |---    |
|view Profile   | user can view Profiles                | Pass|
|review view    |user can see reviews in the profile    | Pass|
|edit profile   |user can edit and update profile       | Pass|
|Delete profile |user can delete profile                | Pass|



## Features

**Features planned:**
* User Profile - Create, Read, Update and Delete.
* Profiles - Users can read other users profiles.
* Users can add review to profiles.
* Users can login to their account.
* Users can logout of their account.
* Users need to be registered and logged in to access Profile creation and 
  editing.
* Responsive Design - the site needs to be fully responsive to cover the wide variety of devices.



## Testing

### Testing Strategy
I did manual testing for the development of the site.



#### Testing Overview

Testing was divided into different sections to ensure everything was tested individually with test cases developed for each area.


#### Validator Testing
All code files were validated using suitable validators for the specific language.
HTML  & CSS code passed the validation.

All validation screenshots are included below.

All HTML validation returned without error
![HTML Validation]()
![CSS Validation]()
![JS Validation]()


#### Lighthouse Testing
Below you can see the results of Googles Lighthouse Testing.

![Lighthouse Testing]()


#### Python/JavaScript Testing
All Custom Python & JavaScript code was manually tested multiple times during and after development.
This is reflected in the fact that all of the user stories below are working and have produced no errors in the terminal or the console.


## Bugs


## Technologies

* Python
* Django
    * Django was used as the main python framework in the development of this project.
* Heroku
    * Was used as the cloud based platform to deploy the site on.
* Heroku PostgreSQL
    * Heroku PostgreSQL was used as the database for this project during development and in production.
* JavaScript
    * Custom JavaScript was utilised to allow Users to close site messages.
* Bootstrap 5
    * Bootstrap was used for general layout and spacing requirements for the site.
* Font Awesome
    * Was used for access to several icons for different sections where icons were appropriate.
* CSS
    * Custom css was written for a large number of areas on the site to implement custom styling and escape a bootstrap look and feel to the site.
* Jinja/Django Templating
    * Jinja/Django templating language was utilised to insert data from the database into the sites pages. It was also utilised to perform queries on different datasets.
* HTML
    * HTML was used as the base language for the templates created for the site.

#### Packages Used

* VS Code & Gitpod was used to develop the site
* Git was utilised for version control and transferring files between the code editor and the repository
* GitHub was utilised for storing the files for this project

#### Resources Used

* The Django documentation was used extensively during development of this project
* The Cloudinary documentation was used.
* The Code Institute reference material was used as a general reference 
* The Django walk through project 'I think before I Blog'




## Deployment

The site was deployed via Heroku, and the live link can be found here - [Freelance Beauticians](https://pp4-beautysalon.herokuapp.com/)

### Project Deployment

- To deploy my project on Heroku, I followed these steps:
   -Signed up or logged in to Heroku.
    -From the main dashboard, clicked "New" and selected "Create New App".
    -Entered a unique name for the project and selected a suitable region, then clicked "Create App”.

    -Create Database in ElephantSOL

    Follow the steps to Create PostgreSQL database instance
    -Login/signup to ElephantSQL.com to access your dashboard
    -Click “Create New Instance”
    -Select the Tiny Turtle (Free) plan
    -Select “Select Region” 
    -Select a data center near you
    -Then click “Review”
    -Check your details are correct and then click “Create instance” 
    -Return to the ElephantSQL dashboard and click on the database instance name for this project
    - That’s the database created
    -In the URL section, click the copy icon to copy the database URL

    -Go back to the Heroku dashboard open the Settings tab
    -Add two config vars:
    -DATABASE_URL, and for the value, copy in your database URL from ElephantSQL, no need to add quotation marks.
    -SECRET_KEY containing your secret key.
    - Added the secret key to the Heroku Config Vars as "SECRET_KEY" for the KEY value and the secret key value created as the VALUE.
    -In the settings.py file within the Django app, imported Path from pathlib, os, and dj_database_url.
    -Inserted the line if os.path.isfile("env.py"): import env to import the env.py file if it exists.
    -Removed the insecure default secret key in the settings file and replaced it with SECRET_KEY = os.environ.get('SECRET_KEY').
    -Replaced the databases section with DATABASES = {'default': dj_database_url.parse(os.environ.get("DATABASE_URL"))}.
    -Migrated the models to the new database connection in the terminal
    -Added the Cloudinary libraries to the list of installed apps, with 'cloudinary_storage' above 'django.contrib.staticfiles' and     
        'cloudinary' below it.
    -In the settings.py file, added the STATIC files settings, including the url, storage path, directory path, root path, media url, and   
        default file storage path.
    -Linked the templates directory in Heroku with TEMPLATES_DIR = os.path.join(BASE_DIR, 'templates').
    -Changed the templates directory to TEMPLATES_DIR by adding 'DIRS': [TEMPLATES_DIR] in the settings.py file.
    -Added Heroku to the ALLOWED_HOSTS list in the format "app-name.herokuapp.com".
    -Created three new top-level folders in the code editor: media, static, and templates.
    -Created a Procfile in the top-level directory and added the code web: gunicorn PROJECT_NAME.wsgi.
    -Added the changed files, committed, and pushed to GitHub in the terminal.
    -Navigated to the "Deploy" tab in Heroku and manually deployed the branch, watching the build logs for any errors.
    -After completing the deployment steps, Heroku will build your app. Once the build process is complete, you will receive a message that 
        your app has been successfully deployed, along with a link to the live site that you can visit.


#### Forking the repository


    To make a copy of a GitHub repository without affecting the original one, you can fork it. Here are the steps:
    Log into your GitHub account or create one if you don't have one already.
    Go to the original repository that you want to fork,
    On the top right corner of the repository page, click the "Fork" button.
    GitHub will create a copy of the repository in your own account, which you can view or modify without affecting the original repository.


#### Create a clone of this repository


    To create a local copy of a GitHub repository, you can use the clone command. This allows you to have the same files and code as the original repository at a specific point in time. Here are the steps to follow:
    Go to the repository on GitHub.
    Click on the green "Code" button and select "Clone with HTTPS".
    Copy the URL that is displayed.
    Open your code editor and navigate to the location where you want to clone the repository.
    In the terminal, type 'git clone' followed by the URL you copied from GitHub.
    Press Enter and Git will clone the repository to your local machine.


## Credits

    -All Images used across the site were sourced from either pexels.com, 

    - Social media links were all sourced from Font Awesome.

    - I relied on the  Django walk through projects.
    Further research was done by building walk through projects available freely on youtube 

## Acknowledgements

I would like to acknowledge the help and support given by collegues, our cohort lead Ivette and tutor assitant Rabecca, my mentor Chris Quinn, 



