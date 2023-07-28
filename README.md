# Learn MySQL with Python by Syed Muhammad Mooazam

## MySQL
MySQL is a widely used relational database management system (RDBMS).

MySQL is free and open-source.

MySQL is ideal for both small and large applications.

![image](https://user-images.githubusercontent.com/63813881/173280238-beb91d36-6383-47fb-b818-9c7da0e1e5ab.png)
![image](https://user-images.githubusercontent.com/63813881/173280251-8a30a82e-87c3-4553-b923-54b5298f5f78.png)
![image](https://user-images.githubusercontent.com/63813881/173280261-573b5a22-592d-4580-8b24-1968ffe3e3b1.png)
![image](https://user-images.githubusercontent.com/63813881/173280285-3cae5c91-310f-41f0-9501-dbf20d85ed61.png)

# Download And Installation
https://dev.mysql.com/downloads/installer/

## Step 1:
Go to the official website of MySQL and download the community server edition software. Here, you will see the option to choose the Operating System, such as Windows.

## Step 2:
Next, there are two options available to download the setup. Choose the version number for the MySQL community server, which you want. If you have good internet connectivity, then choose the mysql-installer-web-community. Otherwise, choose the other one.
![image](https://user-images.githubusercontent.com/63813881/173280356-9ca94e07-5ddf-4a40-92c3-253f396c79b7.png)

# Installing MySQL on Windows

## Step 1:
After downloading the setup, unzip it anywhere and double click the MSI installer .exe file. It will give the following screen:
![image](https://user-images.githubusercontent.com/63813881/173280339-f7c8b98a-f97c-4e8b-b2f5-dac12d692281.png)

## Step 2:
In the next wizard, choose the Setup Type. There are several types available, and you need to choose the appropriate option to install MySQL product and features. Here, we are going to select the Full option and click on the Next button.
![image](https://user-images.githubusercontent.com/63813881/173280369-fcea302e-f300-4149-b480-4208362ef840.png)
This option will install the following things: MySQL Server, MySQL Shell, MySQL Router, MySQL Workbench, MySQL Connectors, documentation, samples and examples, and many more.

## Step 3:
Once we click on the Next button, it may give information about some features that may fail to install on your system due to a lack of requirements. We can resolve them by clicking on the Execute button that will install all requirements automatically or can skip them. Now, click on the Next button.
![image](https://user-images.githubusercontent.com/63813881/173280402-a988a5dc-f091-4449-b143-cdaf7423d160.png)

## Step 4:
In the next wizard, we will see a dialog box that asks for our confirmation of a few products not getting installed. Here, we have to click on the Yes button.
![image](https://user-images.githubusercontent.com/63813881/173280408-344e2c75-b3f8-4aa1-b73a-bd2665baa547.png)
After clicking on the Yes button, we will see the list of the products which are going to be installed. So, if we need all products, click on the Execute button.
![image](https://user-images.githubusercontent.com/63813881/173280416-0b73aa80-ab85-405e-bd84-e518fd047d0a.png)

## Step 5:
Once we click on the Execute button, it will download and install all the products. After completing the installation, click on the Next button.
![image](https://user-images.githubusercontent.com/63813881/173280430-e2c297c4-bb2f-4709-82c7-a0a13a316d28.png)

## Step 6:
In the next wizard, we need to configure the MySQL Server and Router. Here, I am not going to configure the Router because there is no need to use it with MySQL. We are going to show you how to configure the server only. Now, click on the Next button.
![image](https://user-images.githubusercontent.com/63813881/173280449-7ee315c3-15d8-48c5-b57f-937c2ded6928.png)

## Step 7:
As soon as you will click on the Next button, you can see the screen below. Here, we have to configure the MySQL Server. Now, choose the Standalone MySQL Server/Classic MySQL Replication option and click on Next. Here, you can also choose the InnoDB Cluster based on your needs.
![image](https://user-images.githubusercontent.com/63813881/173280466-8e31e5ae-bd7e-44ac-8a56-374c0e41a883.png)

## Step 8:
In the next screen, the system will ask you to choose the Config Type and other connectivity options. Here, we are going to select the Config Type as 'Development Machine' and Connectivity as TCP/IP, and Port Number is 3306, then click on Next.
![image](https://user-images.githubusercontent.com/63813881/173280473-8acf6d90-3cbe-4e45-8428-7f6f5fafaeea.png)

## Step 9:
Now, select the Authentication Method and click on Next. Here, I am going to select the first option.
![image](https://user-images.githubusercontent.com/63813881/173280492-bdbca34b-d172-4813-b865-2adf60d8f2ae.png)

## Step 10:
The next screen will ask you to mention the MySQL Root Password. After filling the password details, click on the Next button.
![image](https://user-images.githubusercontent.com/63813881/173280511-5bdf705a-96f4-483d-8516-969864cd8976.png)

## Step 11:
The next screen will ask you to configure the Windows Service to start the server. Keep the default setup and click on the Next button.
![image](https://user-images.githubusercontent.com/63813881/173280530-c078626b-0b6c-4c8f-94dc-13d69a13f578.png)

## Step 12:
In the next wizard, the system will ask you to apply the Server Configuration. If you agree with this configuration, click on the Execute button.
![image](https://user-images.githubusercontent.com/63813881/173280548-c22abf24-54c7-4dac-82af-a08c3e0bf5e9.png)

## Step 13:
Once the configuration has completed, you will get the screen below. Now, click on the Finish button to continue.
![image](https://user-images.githubusercontent.com/63813881/173280555-175ceb56-f710-463f-992b-ed3524f6516f.png)

## Step 14:
In the next screen, you can see that the Product Configuration is completed. Keep the default setting and click on the Next-> Finish button to complete the MySQL package installation.
![image](https://user-images.githubusercontent.com/63813881/173280581-7bdbe189-77ce-4ebc-bb78-c44d545d2d2e.png)

## Step 15:
In the next wizard, we can choose to configure the Router. So click on Next->Finish and then click the Next button.
![image](https://user-images.githubusercontent.com/63813881/173280593-d5933d29-61a4-432b-aac4-44a51257abd6.png)

## Step 16:
In the next wizard, we will see the Connect to Server option. Here, we have to mention the root password, which we had set in the previous steps.
![image](https://user-images.githubusercontent.com/63813881/173280603-1563352a-c972-4230-a624-36f2259ccdb8.png)
In this screen, it is also required to check about the connection is successful or not by clicking on the Check button. If the connection is successful, click on the Execute button. Now, the configuration is complete, click on Next.

## Step 17:
In the next wizard, select the applied configurations and click on the Execute button.
![image](https://user-images.githubusercontent.com/63813881/173280619-90407455-8fcd-4bb5-b2c7-ca341fc5f79c.png)

## Step 18:
After completing the above step, we will get the following screen. Here, click on the Finish button.
![image](https://user-images.githubusercontent.com/63813881/173280630-1760437d-11be-4704-a868-c1c4d9b7c96a.png)

## Step 19:
Now, the MySQL installation is complete. Click on the Finish button.
![image](https://user-images.githubusercontent.com/63813881/173280646-5f4cf713-ab86-40a8-a4b5-658bfa5462b8.png)

# Verify MySQL installation
Once MySQL has been successfully installed, the base tables have been initialized, and the server has been started, you can verify its working via some simple tests.

Open your MySQL Command Line Client; it should have appeared with a mysql> prompt. If you have set any password, write your password here. Now, you are connected to the MySQL server, and you can execute all the SQL command at mysql> prompt as follows:

## For example: 
Check the already created databases with show databases command:
![image](https://user-images.githubusercontent.com/63813881/173280683-4ac11109-c2fa-4087-a6a5-8782b959f179.png)

# What is the Primary key?
A primary key is a single field or combination of fields that contain a unique record. It must be filled. None of the fields of the primary key can contain a null value. A table can have only one primary key.

# Install library in python 
# 1) pip install mysql
# 2) pip install mysql.connector
# 3) pip install mysql-connector-python