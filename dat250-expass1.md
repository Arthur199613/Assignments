# 1. Installation of the development environment

This section was rather smooth. I've opted to install IntelliJ as I have read that it is a user-friendly IDE, and is great for working on small projects. There was no problems  with installation.
  
  
# 2. Validating the development kit 
   
   In order to validate it, I simply created a small project, built it and tested the output. Everything worked as it should. Also I opened the local version of the application that Heroku provides and built it, and there were no errors in terms of compatibility etc.
   
   
 # 3. Technical problems with the Heroku platform
 
 In the beginning I opted for the gradle installation of Heroku; I was able to clone the repository and upload it onto Heroku successfully. However when trying to run the app locally on my own machine I encountered a similar problem to the one they describe; " Unsupported major.minor version 52.0". However my problem whilst similar was : "Unsupported class file major version 60"; which could possibly indicated a higher version of JDK or something else which I was not entirely able to troubleshoot.
 
 However a few days later I simply opened the application in IntelliJ instead of trying to run it from cmd prompt and built the application in there. Afterwards I was able to use the build gradle.bat command and proceed further with the tutorial. I was able to push changes using git, and see them reflected on the Heroku platform.
 
 # 4. Pending issues unable to solve
 
~~The issue outlined in heading 3 was not solved. This may require further troubleshooting.~~

 
URL to the project: https://thawing-harbor-30168.herokuapp.com/
   
  
  
  
  
