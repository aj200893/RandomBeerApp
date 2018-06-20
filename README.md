# RandomBeerApp

A simple web app to show information of random Beer Sample Records from the Database. A user can perform basic CRUD operation to manage the Beer Records.

![output](https://github.com/Anubhavj02/RandomBeerApp/blob/master/output/output1.png)

## Technical Stack
#### Backend
* Java 8
* Spring 4.3.0
* Hibernate 5.2
#### Frontend
* Angular 1.4.9
* Bootstrap 4
* jQuery 3.3.1
#### Database
* MySQL 5.7
#### Testing
* Junit 4
* Mockito 1.9.5
#### Misc
* Maven 3.5.3 (Build Automation Tool)
* Tomcat 7 Server

## Steps to Run:
#### Requirements(only these requirements need to be installed; rest dependencies will be installed through maven)
* Java 8
* Maven 3.5.3
* Tomcat 7

1. Install maven 3.5.3 and set MVN_HOME
2. Install Tomcat 7
3. Clone the repository and change path to the cloned directory
  ```shell
  $ git clone https://github.com/Anubhavj02/RandomBeerApp.git
  $ cd RandomBeerApp
  ```
4. Do maven clean install; this will build the application and run all the test cases
  ```shell
  $ mvn clean install
  ```
5. There are two ways to run on server:
  * Using Maven tomcat plugin
  ```shell
  $ mvn tomcat7:run
  ```
  Access http://localhost:8080/RandomBeerApp
  * Using installed tomcat; after Maven Clean install, a WAR file is made in the target directory
  ```
  Copy the the WAR file "RandomBeerApp/target/RandomBeerApp.war" to "---Your_Tomcat_Directory---/webapps"
  and then; run the tomcat server.
  ```
  ```shell
  $ sh Your_Tomcat_Directory/bin/startup.sh
  ```
  Access http://localhost:8080/RandomBeerApp
  
 ## Output and Screen Shots:
 ### GUI Web
 1. Show Random Beer functionality
 GUI
 ![](https://gph.is/2JTcdX3)
 
 2. Manage Beer
 ![output](https://github.com/Anubhavj02/RandomBeerApp/blob/master/output/output2.png)
 
 3. Add Beer Record
 ![output](https://github.com/Anubhavj02/RandomBeerApp/blob/master/output/output3.png)
 
 4. Edit Beer Record
  ![output](https://github.com/Anubhavj02/RandomBeerApp/blob/master/output/output4.png)
 
 



