# FUTURE READY TALENT VIRTUAL INTERSHIP PROJECT
PROJECT NAME - TWO FACTOR AUTHENTICATION SYSTEM
You can check working function app by this http trigger - https://2fasystem.azurewebsites.net/api/myfirstfunction?name=Demouser&otp_send=Gahpd7
# Resources used:
               * Azure functions(python)
               * Azure Resource manager
               * Visual studio code 
               
               * other resources:- linux os which runs azure function app
               
             
               
 

# Please watch this project demo and explanation vidio created by me for further idea and refference of my project :)
https://user-images.githubusercontent.com/78414877/145254141-86ee0f71-acae-414b-801b-a9f34071d23d.mp4

* Project problem area - to secure system , apps from unauthorized logins and access using two factor authentication concept with help of azure services and python twilio api's
* Project outcomes - we created two factor authentication system with help of HTTP triggered azure function app and python language.
* Description:-
* Firstly we created Http triggered azure function app for python language and we written python function for getting http request from cliet application with help request module in python which help to get and post http requests. we written code for creating one time password which is random string generated by function and we send it to the verified user whatsapp number while user or any unauthorized user try to log in in system or application , which notify the user some tries to log in and as well as otp for log in which saves system from login simply by giving values . this method will increase over all security and privecy of user
* 1)visual studio help to connect to azure portal and our subscription and cloud function apps
* 2)twilio api help to manage whatsapp number send otp to user's registered whatsapp number
* 3)azure function app - which help us deploy our server less apllication and gets https request such as username and generated otp from our client application through http request  which is situated in users workstation and checks for correct username and using twilio api sens otp to user whatsapp number . user will use that otp to login in system or application if its matches with client otp then user will successfully able to login in its own system or it will not allow unauthorized user to login in users system.
# azure function app ![Screenshot (83)](https://user-images.githubusercontent.com/78414877/145259868-60efff03-3a2d-4736-b2f4-b1faa9180ecd.png)
![Screenshot (80)](https://user-images.githubusercontent.com/78414877/145259977-21e889db-ce8f-47ba-b064-edd3d3bf619a.png)
source code 
![Screenshot (84)](https://user-images.githubusercontent.com/78414877/145260527-c1c8a737-beef-4522-bb32-7a3c97917eaf.png)
client application login attemp 
![Screenshot (85)](https://user-images.githubusercontent.com/78414877/145260631-6a960e02-b23a-4e70-a307-ce2599158a45.png)
htpp request triggeered by client app to the azure function app and responded by server function app 
#OTP![Screenshot (86)](https://user-images.githubusercontent.com/78414877/145260836-6c27ce45-e146-4511-bc8f-e48c3d802176.png)
using otp successfully loged in by user
![Screenshot (87)](https://user-images.githubusercontent.com/78414877/145260934-482f2707-08e7-4c24-8d55-2061e7ca5ff6.png)
with wrong otp or erong user login details unauthorized login attemp detected by function and client application
and it will inform to user about unauthorized login by alert messege.
![Screenshot (88)](https://user-images.githubusercontent.com/78414877/145261237-244b4c94-d4b8-4149-8209-1c9603de3b94.png)
Demo http trigger passed through url bar for better understanding how azure function app working and responding .
![Screenshot (89)](https://user-images.githubusercontent.com/78414877/145261466-d7d589c2-3e04-4ff9-a69a-32aa0e1bd14c.png)

Thank You :)




- Bhushan Deshmukh
- bhushansdeshmukh@coep.sveri.ac.in
