# Vertech
Android-Study-Jams
Project Name-Vertech
Problem Statement
Initially every beginner finds it tough to start and work under a domain of their interest due to lack of like-minded mates and guides of the same avenue. Tech geeks find it difficult to connect with people having the same affinity. There is a lack of a proper environment where they can focus and carry out their ideas without getting distracted by interfering and unwanted ads .Android applications are a very convenient way to create an environment where different students(beginners as well as advanced), can share a common platform to create as well as share their project ideas and recent personal achievements.

Solution
Vertech is an ad free instant messaging and digital distribution platform where tech enthusiasts can jam with peers of their respective domains and collaborate on different projects. A league can share feeds of their amuse or new ideas of their respective domain. Many innovative ideas , projects can be cultivated on this user-friendly platform. The user can also maintain a to-do list of the projects to be done with his/her respective team mates.To avoid any delay in the flow of ideas, the user will have the liberty to have secure conversations through messaging with his peers.

Screenshots
Registration Page- ![register](https://user-images.githubusercontent.com/65966441/185752365-d53ca724-6e05-482f-9064-e17371b68efa.jpg)


Home page/Feed Section- ![register](https://user-images.githubusercontent.com/65966441/185752424-69c6fcee-32cf-461a-a373-a0f5abf39a8f.jpg)


User Chats- ![image](https://user-images.githubusercontent.com/65966441/185752443-6e287bb7-1ae3-4c4f-9d65-54f13c2714da.png)


Specific Chat- ![image](https://user-images.githubusercontent.com/65966441/185752467-84df645a-1891-45f8-a8b8-9f26b5dcf563.png)



Todo Projects- ![image](https://user-images.githubusercontent.com/65966441/185752478-39d4d4b7-a422-4f1f-ad38-07c00aa014ef.png)


Create Post- ![image](https://user-images.githubusercontent.com/65966441/185752483-b49c34ed-8de2-4fc6-b5d5-eb8641ad3846.png)


Peer Search- ![image](https://user-images.githubusercontent.com/65966441/185752502-4753a51a-d4dd-47b0-bc5d-65200a0eb9a6.png)


User profile- ![image](https://user-images.githubusercontent.com/65966441/185752516-eb3d723f-7218-4d0a-8c6f-4024fc6e5452.png)


Functionality and Components used
The user interface of our application is made very subtle and easy to use.Following are few of our selection of Kotlin basic concepts to achieve a fairly elevated application :

Constraint Layout: For better performance of the app and to acquire a responsive view we chose this concept which was quite adaptable for different screen sizes. Most of the .xml files of the applications are made using constraint layout.

Navigation Component: To navigate between stations within our app which provides a smooth user experience irrespective of the component used.

View Model: The View Model functionality is used in the ???Feed??? section of the application as well as in the Todo Projects section of the application.

LiveData: The Live data functionality is used in the ???Todo Projects??? section to update the items in the recycler view as well as delete them on click.

Recycler View: This functionality is used in the home page to view daily feed, the chat section as well as in the todo list for making projects.

Room database: The Room database functionality is used to implement the ???Todo Projects??? section. The items of the recycler view(Project Name, Description and Projects Members) are locally stored in the phone???s File Manager in a folder named App DB.

Internet Connectivity: The application uses Firebase Authentication for Login/Sign up and Firebase Realtime Database for the chat functionality as well as for the uploading a post and retrieving all the post in feed of the user.

Demo
Demo Video https://github.com/its-navneet/VerTech/blob/master/VerTech_Demo.gif

Registration Page- 

Application link & future scope-
Currently our app is in the testing phase within our associates and technical clubs.

You can use our application through the following link(APK file) https://drive.google.com/file/d/128Pf0oA-7LETtYypuuJBKtUIILvQOylh/view?usp=sharing

Very soon our application will be launched on Google Play Store and will be functional in our and our adjacent universities. We intend,by the end of the year, most schools and institutions will use our community app to explore, learn and create innovative ideas. We are planning to append a more user-friendly experience and group converse of dedicated domains as well as make use of various APIs to provide the user with innovative project ideas.
