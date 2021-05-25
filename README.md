# Secure your application using Facebook as Identity Provider

In this tutorial you will learn how to use Social login for web application and make the authentication process easier for both developers and for the users with App ID.

## Step 1: Create IBM Cloud Account:

If you don't have an IBM Cloud account create one using the below link. In case you already have an account use the below link to 

Login/Signup: https://ibm.biz/BdfPad  

## Step 2: Create App ID service:

Search for App ID in catalog and create the service 

<img width="629" alt="1" src="https://user-images.githubusercontent.com/16270682/119487375-baa18100-bd72-11eb-8875-2f6cff99f8d3.PNG">
<img width="629" alt="2" src="https://user-images.githubusercontent.com/16270682/119487394-c1c88f00-bd72-11eb-9ba0-15959ddf497f.PNG">


## Step 3: Download the Sample App

Click on Download Sample, select node.js and your application will be saved on your PC 

<img width="553" alt="3" src="https://user-images.githubusercontent.com/16270682/119489342-081eed80-bd75-11eb-993d-983086569603.PNG">
<img width="658" alt="4" src="https://user-images.githubusercontent.com/16270682/119489372-0f45fb80-bd75-11eb-9b78-885cd64e5284.PNG">


extract the zip file, Open terminal/Cmd/windows powershell and navigate to the sample folder.

Run the following build and start the app.

    npm install
    npm start

Open http://localhost:3000/ to check application.

## Step 4: Implementing FB Login Process

Go to Facebook Developers site: https://developers.facebook.com. Click on My Apps

<img width="848" alt="5" src="https://user-images.githubusercontent.com/16270682/119489559-40263080-bd75-11eb-9fab-9bc70740fa92.PNG">

Click on create App

<img width="867" alt="6" src="https://user-images.githubusercontent.com/16270682/119489593-461c1180-bd75-11eb-8b3a-1a416c92bf8e.PNG">

Select consumer, give your app a unique name click on create 

<img width="450" alt="7" src="https://user-images.githubusercontent.com/16270682/119489626-4ddbb600-bd75-11eb-8873-92c27aa0828b.PNG">

Go to your app dashboard, click on product on left side, select Facebook Login 

<img width="632" alt="8" src="https://user-images.githubusercontent.com/16270682/119489711-651aa380-bd75-11eb-9369-f04c1bdcf920.PNG">
<img width="666" alt="9" src="https://user-images.githubusercontent.com/16270682/119489761-7663b000-bd75-11eb-9b92-190a036562ee.PNG">


Go back to App ID Dashboard on IBM Cloud, select Identity provider, click on facebook and copy Redirect URL for Facebook Developer Console

<img width="878" alt="10" src="https://user-images.githubusercontent.com/16270682/119489780-7cf22780-bd75-11eb-87dc-9cacd1589157.PNG">

Now go back to facebook console, From Product under facebook login select settings and add  Redirect URL and click on save changes 

<img width="919" alt="12" src="https://user-images.githubusercontent.com/16270682/119489801-83809f00-bd75-11eb-9f2f-4fd06a675845.PNG">

From under the dashboard select settings and click on basic. Copy App ID and App Secret 

<img width="363" alt="13" src="https://user-images.githubusercontent.com/16270682/119489866-96936f00-bd75-11eb-850a-f8693f1b2c26.PNG">
<img width="744" alt="14" src="https://user-images.githubusercontent.com/16270682/119489893-9dba7d00-bd75-11eb-97e0-2e2cd33e8e34.PNG">


Go back to Go back to App ID Dashboard on IBM Cloud, select Identity provider, click on facebook and paste the App ID and App Secret copied in previous step 

<img width="668" alt="15" src="https://user-images.githubusercontent.com/16270682/119489981-b6c32e00-bd75-11eb-9807-e015e349787f.PNG">





