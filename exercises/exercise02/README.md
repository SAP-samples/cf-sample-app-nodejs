# Exercise 02: Create And Access Trial Account
## Objective
In this exercise you'll create a space. You will also get familiar with specific terms such as regions, Global accounts, subaccounts, organization, and space. 

-------

__Let us use the SAP Cloud Platform cockpit__

1.Log on to the SAP Cloud Platform account from the [SAP Cloud Platform](http://cloudplatform.sap.com) web page.
<br><br>
![Login](/img/login.png?raw=true)
<br><br>

2.In the breadcrumb navigation bar, choose **Home**.
<br><br>
![Home](/img/home_nav.png?raw=true)
<br><br>
3.Choose **Start Cloud Foundry Trial**.
<br><br>
![Start Cloud Foundry Trial](/img/home_pg.png?raw=true)
<br><br>
4.Select a region to create your trial account.
<br><br>
![Region](/img/region.png?raw=true)
<br><br>

5.Choose **OK**. This automatically initiates the process of creating a Global account, Subaccount, Organization, and space.
<br><br>
![Global_acc](/img/Global_acc_creation.png?raw=true)
![Org creation](/img/org_creation.png?raw=true)
![Space creation](/img/space_creation.png?raw=true)
<br><br>
6.Choose **Go to Space**.
<br><br>
![Go to Space](/img/post_acc_creation.png?raw=true)
<br><br>
__Let us use the Cloud Foundry command line interface to create and access Trial account__

1.Open the command line interface window. Provide command to set the API endpoint to specific Cloud Foundry region and log on to the SAP Cloud Platform. Enter the following Cloud Foundry commands one after the other:
 
+ **cf api api.cf.**<host information>
<br><br>
![API Endpoint](/img/api_endpoint.png?raw=true)
<br><br>

+ **cf login**

The prompt to enter email and password appears. Enter the details as provided during registration. The SAP Cloud Platform authenticates your credentials and displays the organization and space for your user account.
<br><br>
![CF Login](/img/cf_login_console.png?raw=true)
<br><br>
2.Enter the command **cf target**. This command displays the default organization and space for your account. In case of multiple organizations, it allows you to set a default organization and space within the organization.
