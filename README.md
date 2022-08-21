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
![ProcessingDetail](https://user-images.githubusercontent.com/40983235/185799871-95b1cd5a-5917-4f56-bf92-489c4f471295.jpg)
<img width="960" alt="PaymetDue" src="https://user-images.githubusercontent.com/40983235/185799916-e1b5b59d-3f47-4be3-b447-62b237b581ea.PNG">


## Processing Charge Paymet Getway
<img width="960" alt="PaymentGateway" src="https://user-images.githubusercontent.com/40983235/185799967-c4603bbf-9e94-4229-92f6-41ad498b408f.PNG">

# Developed by:

Pankaj Naik
