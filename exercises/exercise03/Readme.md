# Exercise 03: Deploy and Launch Node.js Application
## Objective

In this exercise, you will get familiar with the application manifest file and its content. You will modify the content of this file and deploy the application from the cockpit. You also have the option to deploy the application from the command line interface.

-----

__Let us use the SAP Cloud Platform cockpit__

1.Clone the content of the git repository available at the [GitHub link](https://github.infra.hana.ondemand.com/TechEd2017/hello-nodejs) using the command
**git clone https://github.infra.hana.ondemand.com/TechEd2017/hello-nodejs**.

2.Compress the contents of the folder **hello-nodejs** to zip file format.
<br><br>
![Zip File](/img/zip_file.png?raw=true)
<br><br>

3.Navigate to the project folder on your local system.

4.Open the **manifest.yml** file in an editor.

5.Provide a unique host value.
<br><br>
![Manifest](/img/manifest_host.png?raw=true)
<br><br>

6.Save the changes.

7.Choose the default “dev” space.
<br><br>
![Space](/img/space.png?raw=true)
<br><br>

8.Choose **Deploy Application**.
<br><br>
![DeployApp](/img/deploy_app.png?raw=true)
<br><br>

9.In the **Deploy Application** dialog, provide the following:

 + Choose **Browse** to navigate and select the compressed file (ZIP) for the application.
 + Select **Use Manifest**.
 + Choose **Browse** to navigate and select the manifest file.
 + Choose **Deploy**.
 <br><br>
 ![DeployApp](/img/dep_app.png?raw=true)
<br><br>
**Result:**<br>
The application is uploaded to the SAP Cloud Platform. The application is automatically started and the resources consumed by the application are displayed.
<br><br>

10.Choose the name of the application. The application overview page appears.

11.From the **Application Routes** section, choose the link to start the application.
<br><br>
![App Routes](/img/app_routes_section.png?raw=true)
<br><br>


 **Result:**<br><br>

The application appears in a new tab.

<br><br>
![App](/img/app.png?raw=true)
<br><br>

__Let us use the Cloud Foundry command line interface to deploy and launch the application.__

1.Navigate to the project folder on your local system.

2.Open the **manifest.yml** file in an editor.

3.Change the name of the application. This is to ensure that applications to be deployed on the SAP Cloud Platform has a unique name.
<br><br>
![Change Name](/img/change_app_name_mani.png?raw=true)
<br><br>

4.Save the changes.

5.Update the new application name in the **package.json** file.
<br><br>
![Package JSON](/img/pack_json_name_chg.png?raw=true)
<br><br>

6.Save the changes.

7.Navigate to the project folder using the command **cd {path of the project folder}**.

8.Enter the command **cf push**. The application is uploaded and the resources consumed by the application are displayed.
<br><br>
![Push Command](/img/app_started.png?raw=true)
<br><br>
