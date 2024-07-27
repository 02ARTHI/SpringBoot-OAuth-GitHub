# SpringBoot-OAuth-GitHub
## About:
Most web applications require an authentication mechanism. It can be tedious to maintain user information and credentials as part of the application. Leveraging OAuth 2 to login or register with well-known social platforms like GitHub, facebook, google and linkedIn is a smart way to integrate a trusted login mechanism into the app. <br>

### Modifications:
Add the client id and client secret properties in application.properties file <br>
Enable Authentication on the app by adding spring security dependency to the POM.xml file. If you build and start the app now, you should be able to see the GitHub login screen. Let’s take it a bit further and try to read the user information sent back by the GitHub api post authentication. 

### ScreenShots: 
 Sign in with GitHub 
![image](https://github.com/user-attachments/assets/381079d9-68ba-4e2a-b43b-8583a3b95192)

![image](https://github.com/user-attachments/assets/b174271a-2a96-4d4b-a436-946c0c84af13)




 
