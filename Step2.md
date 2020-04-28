# Step 2 - Configure ATP and Create APEX Workspace

- Login to Oracle Cloud from cloud.oracle.com. 

- On the left hand menu, choose Autonomous Transaction Processing.

  [![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab400/go_to_atp.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab400/go_to_atp.png)

- You should already have an ATP instance named "WORKSHOP". Click it.

## Configuring auto-scaling

Auto-scaling is a very powerful feature that lets our application handle peaks of traffic, while keeping costs under control at the same time. We will define a minimum number of OCPUs that our ATP will provision and the database will automatically scale up to three times that number, in case the demand arrives.

- Click on Scale Up/Down. [![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/Scale.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/Scale.png)
- Activate the AUTO SCALING checkbox: once you turn this on, the database will use up to three times the number of original cores to execute its workloads. Note on Free Tier this option might not work.[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/Autoscaling.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/Autoscaling.png)

## Accessing the Performance Hub

The Performance Hub is a great tool to monitor our ATP status and activity. It is accessible from the Service Console.

- Open the Autonomous Database Details page and click on Performance Hub. [![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/PerfHubAccess.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/PerfHubAccess.png)
- In the upper part we will see the consumption of resources and waits of our sessions along time. In the lower part, we will be able to check the ASH (Active Session History) analysis, access the SQL Monitoring to analyze individual queries or even submit a session kill command. [![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/PerfHub.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/PerfHub.png)

# Prepare the APEX workspace

- Go to the details of the autonomous database and open the Service Console.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/open_service_console.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/open_service_console.png)

- Go to Development and click on Oracle APEX.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/open_apex.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/open_apex.png)

- You will see the login page for APEX Administration Services. Use the ADMIN password that you entered when you provisioned WORKSHOP ATP instance.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/open_apex_2.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/open_apex_2.png)

- Follow the instructions to create a new workspace.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/create_workspace_01.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/create_workspace_01.png)

- In this case let's call the workspace and database user "**WORKSHOPATP**". 
- **Keep a note of the password as you will need it later.**

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/lab100/create_workspace_02.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/lab100/create_workspace_02.png)

[Lab 103](https://github.com/shaukatdesai/nexttraining/blob/master/Step3.md)

[Back to Labs](https://github.com/shaukatdesai/nexttraining/blob/master/README.md)