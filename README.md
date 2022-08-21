# Return-Order-Management-System
A leading Supply chain Management Organization wants to automate the return orders, by classifying them to repair or replacement. 
Repair is for all main or integral part of their product. Replacement is for accessories.


## System Architecture Diagram

![image](https://user-images.githubusercontent.com/35097948/168974448-134243f9-ef35-405b-87e9-9461613386b1.png)


---------------------------------------- Workflow Board ---------------------------------------

## WorkFlow 

![IMG_0273](https://user-images.githubusercontent.com/35097948/168906599-0bd209a0-2297-46f1-8bf8-2cf04c6af6a5.JPG)

----------------------------------------  Requriment ---------------------------------------

API BaseURL : http://localhost:9191

Login EndPion: /auth/login
# Sample :
<img width="627" alt="authlogin" src="https://user-images.githubusercontent.com/40983235/185799464-33fd07f8-6497-44c7-b836-3f579b5516c4.PNG">

Authentication EndPion: /auth/validate?userName=PAN9
# Sample :
<img width="635" alt="ValidateUser" src="https://user-images.githubusercontent.com/40983235/185799525-93427440-45a8-47bc-94a8-3e5a4bde7f28.PNG">
ProcessDetail EndPion: /return/ProcessDetail
# Sample :
<img width="636" alt="Auth" src="https://user-images.githubusercontent.com/40983235/185799562-cef861ef-6cea-48be-99e6-43b313a80149.PNG">

<img width="642" alt="returnProcessDetail" src="https://user-images.githubusercontent.com/40983235/185799787-3508906b-d20c-463e-8b21-f7ce3f894c77.PNG">


CompleteProcessing EndPion: /return/CompleteProcessing/{requestId}/{cardNumber}/{creditLimit}/{processingCharge}
# Sample :
<img width="630" alt="1auth" src="https://user-images.githubusercontent.com/40983235/185799622-3bd4b214-cabb-4e33-813a-00b32ce9964d.PNG">

<img width="636" alt="CompleteProcessing" src="https://user-images.githubusercontent.com/40983235/185799633-cdac208d-17cc-4aae-9bb0-3758ea6db8f4.PNG">

----------------------------------------  Extra Features ---------------------------------------

ProcessDetails URL: http://localhost:9191/return/ProcessDetail/{userName}
# Sample :
<img width="641" alt="ProcessDetail" src="https://user-images.githubusercontent.com/40983235/185799669-54dfe131-e54e-4c15-86bd-e92959363e0e.PNG">

registerNewUser URL: http://localhost:9094/registerNewUser
# Sample :

<img width="636" alt="Newuser" src="https://user-images.githubusercontent.com/40983235/185799696-7e716ab2-880a-483c-8bb3-374f79935716.PNG">



----------------------------------------  UI Features ---------------------------------------


# Development server
Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

## Log in: 
![LoginSnip](https://user-images.githubusercontent.com/40983235/185799817-eaac9ccc-bed6-47d8-8db7-560e2c1576a0.jpg)


## Processing  
![image](https://user-images.githubusercontent.com/35097948/168912966-50d42c6b-f2e5-4c99-82fa-7dbf65701de9.png)
![image](https://user-images.githubusercontent.com/35097948/168913023-b9db2846-674d-4e0e-bbfd-61e2ce9f0cef.png)
![image](https://user-images.githubusercontent.com/35097948/168913080-124a7e16-2d0f-429c-83a0-7294c1c48d02.png)

## Processing Charge Paymet Getway
![image](https://user-images.githubusercontent.com/35097948/168913168-e2bbb8d8-63ad-4e4f-87db-a54c87759af1.png)




# Developed by:

Pankaj Naik
