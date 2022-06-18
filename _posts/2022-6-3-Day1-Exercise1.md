## How to set up a trial account in the SAP Business Technology Platform

**You will learn**
•	How to set up a trial account in SAP cloud platform. (Steps 1- 7)
•	How to set up the SAP HANA Cloud instance. (Steps 8-11)
•	How to subscribe to the applications. (Step 12)
•	How to access the SAP WEB IDE for SAP HANA Development. (Step 13)
•	How to register to cloud foundry organization (Step 14)

###Step 1- Go to the link and register with your free trial account with your email address. 

Open the [link](https://account.hana.ondemand.com/#/home/welcome) in the browser and select the ***“Register”*** button to initiate the registration process.

 

###Step 2- Fill in the personal details
Update your personal details, check the terms & conditions and then click on ***“Submit”***
 


###Step 3- Save your UserID
Upon successful registration, save your UserID
 

###Step 4 – Log on to the SAP BTP Cockpit  
Click on the link https://cockpit.hanatrial.ondemand.com/cockpit#/home/trial  .You will be requested to verify your mobile number
 
Go through the terms & conditions and then acknowledge by selecting the check box and the click on “ACCEPT” and follow the next steps.

 

 
###Step 5 – Set up your region
 Once your mobile number is verified, then you can select the US East (VA) – AWS cloud  region. 

###Step 6- Set up the Global Account, Sub account, Org and Space.
 After you have selected your Region in the step 6, the Global account, Subaccount, Org & Space will get automatically created.
Ensure that this step is completed successfully and a “DEV” space gets allocated for your account.
 
Click on Continue and then click on the “Enter Your Trial Account”.  
 

###Step 7 – Explore your trial account.
You can now view the Global account, Sub Account details. 
 
 
###Step 8 – Explore your sub account.
Click on the “trial” (as highlighted in the snapshot). This will redirect you to the Overview page of your SubAccount 
 

Ensure that you have the “dev” Space created for your trial account. (This is done automatically). You can find it under the “Cloud Foundry Environment” section.
 

###Step 9 – Explore your “dev” Space and Create an instance of SAP HANA Cloud.
Click on the “dev” Space (as highlighted in the snapshot). This will redirect you to the navigation page of your “dev” Space
 

Once you are inside your “dev” Space, from the left hand menu, select the “SAP HANA CLOUD” and then click on “CREATE”  “SAP HANA Database”
 

 
###Step 10 – Steps for creating SAP HANA Database on the SAP HANA Cloud.
After clicking on the “Create SAP HANA Database” in step 10, a new window will pop up, select “Sign in with Default identity provider”
 
Select the Type as “SAP HANA Cloud, SAP HANA Database” and then click on “Next”
 

Under the General section, enter the instance name as “HANADB”
The admin user name for the database instance is DBADMIN, you must enter a password and then click on “Next”
 

The trial version of the SAP HANA Cloud instance is provided with following configuration: 
 


 

 
 

 
 

 

 

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
