# Exercise 08: Bind Data Source to the Application
Let us use the cockpit option to bind application.
1. Navigate to the space on your trial account.
<br><br>
![Trial Space](/img/dev_space.png?raw=true)
<br><br>
2. Navigate to **Services > Service Marketplace**.
<br><br>
![Service Marketplace](/img/services.png?raw=true)
<br><br>
3. To create a service instance of PostgreSQL, choose **PostgreSQL**.
4. From the navigation screen, choose **Instances**.
5. Choose **New Instance**. The **Create Instance** wizard appears. 
<br><br>
![Service Instance](/img/service_instance.png?raw=true)
<br><br>
6. Use the wizard, choose the service plan and choose **Next**.
7. Skip the next optional step of specifying parameters.
8. In the process, choose the application for binding and provide a name for the service instance.
<br><br>
![Application Name](/img/app_name.png?raw=true)
<br><br>
9. Specify the name for the instance and choose **Finish**.
The service instance is created and the application is bound to the application.
10. Restart the application and launch the application in the browser. The application shows the binding service as well.
<br><br>
![Application](/img/app_bound.png?raw=true)
<br><br>
11. To view the connection details, navigate to the environment variables screen. Choose space > application name. The application overview page appears. 
12. From the application, choose **Environment Variables**.
<br><br>
![Environemt Variable](/img/env_variables.png?raw=true)
<br><br>
13. After binding a service instance to your application, Cloud Foundry adds connection details to the VCAP_SERVICES environment variable when you restart your application.
<br><br>
![VCAP Services](/img/VCAP_Services.png?raw=true)
<br><br> 