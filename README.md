# Social_Integration_App
To integrate Facebook/Gmail login in android application.

# steps:
1. configure android app on google developer acc
2. get configuration file from that
3. enable google sign in & generate certification file
4. download google.services.json file to integrate into android application
5. paste google.service.json into android app
6. add internet permission - manifest.xml
7. add dependecy - build.gradle

# methods
1.Auth.googleSigninAPI.getSignIntent() : to login through google sign in api
onConnectionFailed(connectionResult) : return connection failuare result
2. GoogleSigninAccount class : basic info of class
3. profileActivity. java class : display user details after login

SHA1 key: unique identity of your application authenticating your client
clinet authentication key 
secure hash key in cryptographic

keyhash : usec by the facebook console to indentify your application.


# Login
![WhatsApp Image 2022-01-20 at 8 25 23 PM](https://user-images.githubusercontent.com/91388114/150397492-e6c77652-a687-4068-898a-91958fd5a724.jpeg)
# Facebook
![WhatsApp Image 2022-01-20 at 8 25 23 PM (1)](https://user-images.githubusercontent.com/91388114/150397541-3998a6f6-94a4-4863-8250-9123f854f8d4.jpeg)
# Google
![WhatsApp Image 2022-01-20 at 8 25 23 PM (2)](https://user-images.githubusercontent.com/91388114/150397582-5186c7fa-bd44-439d-8549-9e9f7b73a2fe.jpeg)
![WhatsApp Image 2022-01-20 at 8 25 23 PM (3)](https://user-images.githubusercontent.com/91388114/150397606-cfe628e5-b8b0-401b-b027-7abd2410d6ef.jpeg)
![WhatsApp Image 2022-01-20 at 8 25 23 PM (4)](https://user-images.githubusercontent.com/91388114/150397630-b48e3a2d-6314-4aaf-be60-eaa39ed9837e.jpeg)
