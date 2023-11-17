# Communi Connect Web App

## Project Overview

The Communi Connect Web App is a platform designed to address and resolve ongoing community problems by harnessing the collective input and concerns of community members. Its primary purpose is to facilitate efficient communication between community members and authorities, ultimately leading to actionable solutions and improved community well-being.

### Key Goals

- Allow every member of the community to post their problems while maintaining their anonymity.
- Create a user-friendly and accessible platform for community members to voice their concerns.
- Foster a sense of community engagement and collaboration to address issues effectively.
- Drive positive change within the community by providing a platform for actionable solutions.

## Installation

To set up the Communi Connect Web App, follow these steps:
1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/TejeswarReddy03/Communi_Connect_Web_app.git
### Node Installation
Node js version used in the project is 9.5.1.
Make sure you install this node js version on your systems.

### Backend Installation

1. Navigate to the `backend` folder:

   ```bash
   cd backend
2.Install the required backend dependencies using npm:

    
    npm install
If you encounter any errors during the installation process, you may need to install the dependencies explicitly. Run the following commands to install the dependencies separately:
example:npm install express
      npm install mongoose
### Frontend Installation
1. Navigate to the `frontend` folder:

   ```bash
   cd frontend
2.Install the required frontend dependencies using npm:

    
    npm install
If you encounter any errors during the installation process, you may need to install the dependencies(displayed as notfound in terminal) explicitly. Run the following commands to install the dependencies separately(All the versions of the packages can be seen in package.json file):
example:
```bash
npm install express
```
```bash
npm install mongoose
```

### Usage
To run the Communi Connect Web App, follow these steps:
## Starting frontend
1.After installing dependencies, make sure to put your keys and configuration in a .env file in the root directory of backend folder and go to frontend dir:

   ```bash
   cd frontend
   ```
2.Start the frontend server:

   ```bash  
    cd frontend
    npm start
   ```

## Starting backend
(Follow the below steps only if you want to run your backend through your mongodb_keys otherwise you can use the backend of the owner maintaining that repo as the repo already has backendlink deployed and setup)

3.Insert Environmental api keys inside env.js file otherwise its not possible to run backend server. 

4.Open another terminal and go the project directory.

5.Start the backend server:
   ```bash
   cd backend
   node ./index.js
  ```

These commands will start both the frontend and backend components of the Communi Connect Web App.
You can then access the application by opening it in your web browser.
You can change the port as per  your system.

Note: Make sure you give origin of cors for socket.io(which is present in index.js of backend directory) same as the port in which frontend is running

## Features

### How to Use

#### User Registration and Login

1. **User Registration:**
   - Upon visiting the website, new users are directed to the signup page by clicking "register/signin user" in startpage.
   - Fill out the required registration information.
   - After successful registration, you will be redirected to the login page.

2. **User Login:**
   - Enter your credentials (email and password) to log in.
   - for testing : USE  email:john@gmail.com password:1234567 with pincode 123456

#### Admin Registration and Login

1.**Admin Registration:**
   - Upon visiting the website,new admins are directed to admin signup page by clicking "register/signin admin" in startpage.
   - Fill out the required registration information.
   - Based on the information you enter,you will receive "adminID" through email.
   - AdminId is mandatory while you login as admin.
   - After successful registration,you will be redirected to the login page.

2.**Admin Login**
   - Enter your credentials(email,AdminID and password) to login

#### Home Page Navigation

3. **Home Page:**
   - Upon successful login, you will be redirected to the home page.
   - Here, you can learn more about the web app and its features.

4. **Navigation Menu:**
   - The navigation menu allows you to access various sections of the website, Announcements,Maps,Chats,Posts,WeeklyAnalysis,Profile.

5. **Feedback section:**
   - There is a feedback section at the end of the homepage(scroll down), through that form you can send your feedback and people managing the website will receive that info through email.


#### Maps

6. **Maps:**
   - Use the "Add Marker" feature on the top left to mark noteworthy incidents on the map in your pincode area.
   - Note that all fields are mandatory, and specific conditions must be met, such as minimum and maximum radius values.

#### View Markers

7. **View Markers:**
   - View markers in your pincode area based on your current location and the radius of the marker.
   - If you fall within the marker's radius, you can see its description, images, and other details.

#### Posts

8. **Posts:**
   - Post content by mentioning your username and content and should add image(image is mandatory).
   - user can view the posts posted in all pincodeareas.
   - user can also post anonymously.
   - user can comment,like,unlike a post.
   - Both user and admin have the authority to delete any post.
   - The "Posts" section is vital for sharing information within the community.

#### Chats

9. **Chats:**
   - Use this section to chat with individuals who fall within the same pincode area.

#### Announcements

10. **Announcements:**
   -Onclicking announcements ,you will see three subsections  Announcements,MultilingualAnnouncements,polls.
   1.**Announcements(subsection)**
   - Important information can be conveyed through announcements.
   - If you login as user then you can only view the announcements.Inorder to post the announcement,you need to be an admin.
   - New announcements are sent to users(of samepincode as of admin) via email.
   - You can also use filters to sort and access specific announcement data.
   
   2.**MultilingualAnnouncements**
   - This section will enable the user to view announcements in a specific language selected by the user.

   3.**Polls**
   - Admin can submit the poll form in this section and users belonging to the same pincode area will see the recently submitted form of their respective admin.
     

11.**WeeklyAnalysis:**
  - At the bottom of the page,you can view number of posts made in the last week across all the pincode areas.
  - On the right of the page,you can view top liked posts and their contents.
  - On the left side,by entering the respective pincode area,you could see usercounts(number of people registered in that pincode area),announcements count,markers count.

#### Profile

12.**EditProfile**
   - User can edit his details in this section.
     
13. **Logout:**
    - To log out, click on the "Logout" option in the navigation menu.
   
#### ChatBot
   - through the chatbot,you can get to know about the website.

These steps outline how to use the various features of the Communi Connect Web App effectively. 

Explore the different sections to contribute to your community and stay informed about important matters.



















   
