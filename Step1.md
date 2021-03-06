# Step 1: Provision an Autonomous Transaction Processing database

- Login to Oracle Cloud from cloud.oracle.com
- On the left hand menu, choose Autonomous Transaction Processing.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/prereq/go_to_atp.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/prereq/go_to_atp.png)

- Select the compartment you previously created
- Choose to create a new instance.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/prereq/create_atp_01.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/prereq/create_atp_01.png)

- Choose any name for the database, in this case "WORKSHOP".

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/prereq/create_atp_02.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/prereq/create_atp_02.png)

- Choose the Transaction Processing option. This will optimize the database for daily transactional processing.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/prereq/create_atp_03.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/prereq/create_atp_03.png)

- Choose Shared Infrastructure for deployment type.

![image-20200428124103977](image-20200428124103977.png)



[](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/prereq/create_atp_free.png)

- Leave the database version with the default value.  Note: For Free Tier you can only select an earlier version.
- Uncheck the Auto Scaling option - we will look at this in the next lab
- Set the admin password. ***Make a note of this as you will need it in the next lab**.*

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/prereq/create_atp_04.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/prereq/create_atp_04.png)

- Create the database.

[![img](https://github.com/oracle/cloudtestdrive/raw/master/ATP/APEX/images/prereq/create_atp_05.png)](https://github.com/oracle/cloudtestdrive/blob/master/ATP/APEX/images/prereq/create_atp_05.png)

This process typically completes within about 5 minutes, after which you will see the status "AVAILABLE".

[Lab 102](https://github.com/shaukatdesai/nexttraining/blob/master/Step2.md)

[Back to Labs](https://github.com/shaukatdesai/nexttraining/blob/master/README.md)