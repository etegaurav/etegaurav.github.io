---
layout: post
title: 1. How to set up a trial account in the SAP Business Technology Platform
background: '/images/pexels-pixabay-270700.jpg'
---


**You will learn**

- How to set up a trial account in SAP Business Technology platform. (Steps 1- 7)
- How to set up the SAP HANA Cloud instance. (Steps 8-11)
- How to subscribe to the applications. (Step 12)
- How to access the SAP WEB IDE for SAP HANA Development. (Step 13)
- How to register to cloud foundry organization (Step 14)

### Step 1- Register a free trial account. 

Open the [link](https://account.hana.ondemand.com/#/home/welcome) in your browser and select the `Register` button to initiate the registration process.

![1-1](/images/1-1.jpg "Register")

### Step 2- Fill in the personal details
Update your personal details, check the terms & conditions and then click on `Submit`

![1-2](/images/1-2.jpg "Fill details")
 
### Step 3- Save your UserID
Upon successful registration, save your `UserID`

![1-3](/images/1-3.jpg "Save UserID")

### Step 4 – Log on to the SAP BTP Cockpit  
Click on the [link](https://cockpit.hanatrial.ondemand.com/cockpit#/home/trial). You will be requested to verify your mobile number. After successful verification of number, click on `Continue`.

![1-4](/images/1-4-1.jpg "Verify telephone number")

Go through the terms & conditions. Acknowledge by selecting the check box and the click on `ACCEPT` and follow the next steps

![1-5](/images/1-4-2.jpg "Verify telephone number")

### Step 5 – Set up your region

After successful registration, you will be redirected to set up your region in the SAP HANA cloud. Select the `US East (VA) – AWS cloud  region`

![1-5](/images/1-5.jpg "Select US EAST (VA)- AWS Cloud region")


### Step 6- Set up the Global Account, Sub account, Org and Space.

After you have selected your Region in the previous step, the `Global account`, `Subaccount`, `Org` & `Space` will get automatically assigned to your account.
Please wait and ensure that this step gets completed successfully for your account.

![1-6](/images/1-6.jpg "Account Set up")
 
Click on `Continue`. You will be directed to the SAP BTP cockpit, click on `Enter Your Trial Account”`

![1-6-2](/images/1-6-2.jpg "Go to your trial account")

### Step 7 – Explore your trial account.
You can now view the Global account, Sub Account details. 

![1-7-2](/images/1-7-2.jpg "Explore account")
 
### Step 8 – Explore your sub account.

Click on the `“trial”` (as highlighted in the snapshot). This will redirect you to the Overview page of your SubAccount 

![1-8-1](/images/1-8-1.jpg "Subaccount overview") 

Ensure that you have the `“dev”` Space created for your trial account. (This is done automatically). You can find it under the `“Cloud Foundry Environment”` section.
 
![1-8-2](/images/1-8-2.jpg "Dev Space")

### Step 9 – Explore your “dev” Space and Create an instance of SAP HANA Cloud.
Click on the `dev` Space (as highlighted in the snapshot). This will redirect you to the navigation page of your “dev” Space

![1-9-1](/images/1-9-1.jpg "Dev Space")

Once you are inside your `dev Space`, from the left hand menu, select the `SAP HANA CLOUD` and then click on `CREATE` --> `SAP HANA Database`
 
![1-9-2](/images/1-9-2.jpg "SAP HANA Cloud")

![1-9-3](/images/1-9-3.jpg "Create SAP HANA DATABASE")
 
### Step 10 – Steps for creating SAP HANA Database on the SAP HANA Cloud.
After clicking on the “Create SAP HANA Database” in the previous step, a new window will pop up, select `Sign in with Default identity provider`

![1-10-1](/images/1-10-1.jpg)
 
Select the `Type` as `SAP HANA Cloud, SAP HANA Database`  and then click on `Next`

![1-10-2](/images/1-10-2.jpg)

Under the `General` section, enter the instance name as `HANADB`
The admin user name for the database instance is `DBADMIN`, you must **enter a password** and then click on `Next`

![1-10-3](/images/1-10-3.jpg)

Under the `SAP HANA Database` section, the max memory available in trial version is 30GB. Enter 30 GB as memory and then click on `Next`

![1-10-4](/images/1-10-4.jpg)

Under the `SAP HANA Database Availability zone and Replicas` section, no action is required as Availability zone and Replicas is not available for trail instance. Click on `Next` to proceed further.

![1-10-5](/images/1-10-5.jpg)

Under the `SAP HANA Database Advanced Settings`, Select `Allowed all IP addresses` as shown below and click on `Next` to proceed further.

![1-10-6](/images/1-10-6.jpg)

Under the `Data Lake` section, no action needed. Click on `Review and create`.

![1-10-7](/images/1-10-7.jpg)
 
Review the details and then Click on `Create Instance`

![1-10-8](/images/1-10-8.jpg)

Click on the `Refresh` icon to view the status of SAP HANA database instance creation. This will take about 10 – 15 mins depending upon the load on the cloud service providers.

![1-10-9](/images/1-10-9.jpg)
 
After few minutes, refresh again to view the status. It should be in ![1-10-11](/images/1-10-11.jpg) status.

![1-10-10](/images/1-10-10.jpg)
 

**Congratulations!!**, you have now successfully set up your **SAP HANA Cloud Database** Instance.





 


 

 
 

 
 

 

 

***********************************************************************************
Click on the “Step 3”. Leave the settings for Data Lakes as they are and move on to the next step.
 
Click on the “Step 4”.  Select the option “Allow all IP addresses” under the Allowed Connections and then click on “Create Instance”. 
 

After clicking on the “Create Instance” button you will be redirected to a page which will create the SAP CLOUD INSTANCE. This will take about 10 – 15 mins depending upon the load on the cloud service providers.

 
After waiting for sometime, the SAP HANA Cloud instance will be up and have  state.
Congratulations, you have now successfully set up your SAP HANA Cloud Instance.
 

Step 11 – Steps for subscribing to applications.
In this step we will learn to subscribe to two applications:
1. SAP WEB IDE for SAP HANA Development
2. SAP Business Application Studio
Go to the link (https://cockpit.hanatrial.ondemand.com/cockpit#/home/trial) and login to your trial account and then click on “Enter Your Trial Account”.
 
Click on the “trial” (as highlighted in the snapshot). This will redirect you to the navigation page of your SubAccount 
 

Click on the “Subcriptions” (as highlighted in the snapshot). This will redirect you to the subscriptions  page of your SubAccount 
 
 
 
 
In the search bar(present in the right side of the screen highlighted in yellow), type “SAP” and then you will be able to find “SAP Business Application Studio” and “SAP WEB IDE for SAP HANA Development”

 
Click on “SAP WEB IDE for SAP HANA Development” and then click on “Subscribe”. The status will change from  and then will change to  
 
Follow the same steps as before and subscribe to the application “SAP Business Application Studio”
Congratulations, you have now successfully subscribed to the Applications
Step 12 – Steps for accessing the SAP WEB IDE for SAP HANA
Go to your subaccount (Follow step 5,8 & 9). Now you will find that you have 2 active subscriptions.
 

Click on the “Active Subscriptions” and this will take you to the trial subscriptions page. Look out for the application “SAP WEB IDE for SAP HANA Development” and then click on “Go To Application”
 
You will be redirected to the SAP WEB IDE landing page.
 
Step 13 – Steps for setting up your cloud foundry organization and enable the extensions
After successfully setting up the SAP WEB IDE, click on the preferences icon   and then select “Cloud Foundry” under the “Workspace Preferences”.
Under the “Cloud Foundry Space” select the the API Endpoint as “https://api.cf.us10.hana.ondemand.com”
 
After selecting the API endpoint, a screen will prompt and you will be requested to enter the email address and password which was used at the time of registration. Enter the details in the screen once prompted:
 
After authenticating successfully, the “Organization” and “Space” details will get updated automatically.
 
Congratulations, you have now successfully set up your Cloud Foundry Space.
Finally in order to enable the SAP DATABASE Explorer, the following extensions are required.
Click the “Preference” button, then select the “Extensions”, then search by typing “DATABASE” and then finally turn on the extensions by toggling the buttons

 
Congratulations, you have successfully set up your trial account.
