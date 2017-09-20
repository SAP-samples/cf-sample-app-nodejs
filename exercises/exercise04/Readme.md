# Exercise 04: Start and Stop an Application
## Objective
In this exercise, you will get familiar with the various operations performed on an application. You have options to perform this operation using cockpit or command line interface.

----

__Let us use the SAP Cloud Platform cockpit__

1.Navigate to **Applications**.
<br><br>
![App List](/img/App_list.png?raw=true)
<br><br>

2.In the **Actions** column, choose (stop).
The application stops and displays the status.
<br><br>
![App Stop](/img/App_list_stop.png?raw=true)
<br><br>

3.To restart the application, in the **Actions** column, choose (start).

__Let us use the Cloud Foundry command line interface to start and stop the application.__

1.List applications in your account using the command **cf apps**.
<br><br>
![List App](/img/status_app.png?raw=true)
<br><br>

2.To stop the running application, enter the command **cf stop {app_name}**.
<br><br>
![Stop App](/img/stop_cm.png?raw=true)
<br><br>

3.To check the status of the application, enter the command **cf app {app_name}**. 
<br><br>
![Status of App](/img/status_specifi_app.png?raw=true)
<br><br>
4.To restart the application that is currently stopped, enter the command **cf start {app_name}**.
<br><br>
![Restart App](/img/app_restart.png?raw=true)
<br><br>
