# Exercise 07: Check Logs
Let us use the cockpit option for checking resource consumption.
1. In the **Application Overview** page, choose **Logs**. 
<br><br>
![Logs](/img/logs_nav.png?raw=true)
<br><br>

---

:dart: Result:
The logs for the application appears. For analysis of logs, you can choose **Open Log Analysis**. You can also download the logs to your local system.

---
<br><br>
![Cockpit_Logs](/img/logs.png?raw=true)
<br><br>

Let us use the Cloud Foundry command line interface to check resource consumption.

1.Enter the command **cf logs {app_name}**. This command generates real-time log streams. Initiate an activity to view logs. To exit real-time stream, use **Ctrl – C**.
<br><br>
![CF Logs](/img/console_logs.png?raw=true)
<br><br>
2.To view the most recent logs, enter the command, **cf logs {app_name} --recent**.
