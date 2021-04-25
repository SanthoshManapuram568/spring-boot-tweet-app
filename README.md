# spring-boot-tweet-app

This is an social media application , where user can post , like , comment tweets.<br />
He can also search other users who have registred in the application, by searching the user, he/she can like other users tweets and comment it.<br />

# applications needed

The below are the application that I have used for developing this project<br />
1.Spring Tool Suite 4.9 (Link to download it -> https://spring.io/tools)<br />
2.Visual Studio Code (Link to download it -> https://code.visualstudio.com/)<br />
3.MongoDB community server (Link to download it -> https://www.mongodb.com/try/download/community)<br />

# how to use

1.You need to download or clone the repo, one can download the code by cloning or by using the download option ( if downloaded using download option , it will get you a zip file , so you can extract it into a specific folder)<br />
2.After extraction there will be 2 folders, 1 is angular-src and 2 is TweetApp-API<br />
3.open visual studio code and create a new angular project with routing<br />
  Click [here](https://angular.io/tutorial/toh-pt0) how to create a angular project.
4.After the project creation open the project and replace the src with angular src
  Folder which has new angular project(C / D) -> src (folder) 
5.Open the terminal in VSCode and type <b>ng serve</b> or <b>npm start</b>
6.Open Spring Tool Suite and browse the folder where you have unziped the TweetApp-API and set it as your workspace
7.Click the Import Project -> Maven -> Existing Maven Project -> Browse the Folder TweetApp-API<br />
  It will show you the pom.xml file, click FINISH.
9.After importing , if needed update the project , Right click on the updated project -> Maven -> Update Project -> Ok
  Click [here](https://www.lagomframework.com/documentation/1.6.x/java/EclipseMavenInt.html) how to import maven project in Spring Tool Suite.
11.Open MangoDB compass application and click connect
12.After successful connection , create a new Db by clicking CREATE DATABASE -> Enter Database name as usersbda and collection name as users
  Click [here](https://www.bmc.com/blogs/mongodb-compass/#:~:text=First%2C%20open%20your%20MongoDB%20Compass,and%20the%20port%20is%2027017.) how to run and create db in mangodb compass.
13.Open Spring Tool Suite and in the project there will be TweetAppApiApplication.java , Right click on it and run as Java Application
14.Once all the applications are up and running , open the browser and type localhost:4200 , you will see the UI for TweetApp
15.Register -> login -> postTweet 

<h1>Enjoy the Application</h1>

# contact

if any suggestions , [mail me](santhoshmanapuram568@gmail.com){:target="_blank"}

