# Portal4U
This is my college project, it is a website where user can upload complaints and same complaints uploaded by different user are considered as one and the ping gets increased , It also provides Important news announcement and step by step guides to various important documents

# Requirements 
* JDK, Java
* IDLE preferred IntelliJ, NetBeans

# How To Use
1. Simply RUN the project
1. Open "http://localhost:8080/"

# Languages used
* HTML
* CSS
* JS
* SQL
* JAVA(Spring Boot)

# Structure of Protal4U
## Controllers
#### **HomeController** - controller for Home page 
 Url Handled | Usage
 ----------- | ------
  /homepage | Renders Home page
  /         | Renders Home page
  /about    | Renders About page
  /status=search | To check status and show the pop-up
  /status=close  | To close the pop-up
 #### **GuidesController** - controller for Guides page
  Url Handled | Usage
 ----------- | ------
   /documents | Renders Guides page
 #### **NoticeController** - controller for Notice page
  Url Handled | Usage
 ----------- | ------
  /notices | Renders Notice page
 #### **IssueController** - controller for Issue page
  Url Handled | Usage
 ----------- | ------
  /userIssue | Renders User Issue page
  /addIssue  | Stores the complaint in DataBase
 #### **MuncipalController** - controller for Muncipal side pages
  Url Handled | Usage
 ----------- | ------
 /news_update | Render News Update page
  /logout | Logout From Muncipal Side
  /mun | Renders Issue List page
  /update=comment  | updates the comment in DataBase 
  /status=planning  | updates the status to planning in DataBase 
  /status=solved   | updates the status to planning in DataBase 
  /status=ongoing   | updates the status to planning in DataBase 
  /valid   | Validate the credentials
  /login   | Renders the Login page
    
## Repo
* **IssueRepo** - stores complaints submited by user
* **IssueLogRepo** - stores users who uploaded the complait

## Classes
* **Issue** - entity for IssueRepo
* **IssueLog** - entity for IssueLogRepo
* **IssueItem** - Class to store important details of a complaint used while sending data to IssueList page
* **UserIssue** = Class to store all the deatils submited by the user used while getting data from UserIssue page

# Contact Details 
* Email - striker.aryu56@gmail.com
* Github - https://github.com/strikeraryu
