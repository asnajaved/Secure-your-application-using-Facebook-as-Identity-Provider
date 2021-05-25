# Secure your application using Facebook as Identity Provider

In this tutorial you will learn how to use Social login for web application and make the authentication process easier for both developers and for the users with App ID.

## Step 1: Create IBM Cloud Account:

If you don't have an IBM Cloud account create one using the below link. In case you already have an account use the below link to 

Login/Signup: https://ibm.biz/BdfPad  

## Step 2: Create App ID service:

Search for App ID in catalog and create the service 

## Step 3: Download the Sample App

Click on Download Sample, select node.js and your application will be saved on your PC 

extract the zip file, Open terminal/Cmd/windows powershell and navigate to the sample folder.

Run the following build and start the app.

    npm install
    npm start

Open http://localhost:3000/ to check application.

## Step 4: Implementing FB Login Process

Go to Facebook Developers site: https://developers.facebook.com

Click on My Apps

Click on create App

Select consumer, give your app a unique name click on create 

Go to your app dashboard, click on product on left side, select Facebook Login 


Go back to App ID Dashboard on IBM Cloud, select Identity provider, click on facebook and copy Redirect URL for Facebook Developer Console


Now go back to facebook console, From Product under facebook login select settings and add  Redirect URL and click on save changes 

From under the dashboard select settings and click on basic. Copy App ID and App Secret 

Go back to Go back to App ID Dashboard on IBM Cloud, select Identity provider, click on facebook and paste the App ID and App Secret copied in previous step 





