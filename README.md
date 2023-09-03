# Learn MySQL with Python

![MySQL Logo](https://cdn.freebiesupply.com/logos/large/2x/mysql-logo-png-transparent.png)


## What is MySQL?
MySQL is a powerful, open-source Relational Database Management System (RDBMS) trusted by millions worldwide.

## Who Uses MySQL?
MySQL is the go-to choice for developers, startups, and large enterprises. It's versatile and scales seamlessly.

## Why Choose MySQL?

- **Widely Used**: MySQL is a battle-tested RDBMS that has withstood the test of time.
- **Open Source**: It's not just powerful; it's free and open-source, making it accessible to all.
- **Versatile**: Whether you're crafting a small application or a sprawling, complex system, MySQL is your reliable companion.

## What is Primary Key?

A primary key is a single field or combination of fields that contain a unique record. It must be filled. None of the fields of the primary key can contain a null value. A table can have only one primary key.

Now, let's roll up our sleeves and commence our journey!

## Download and Installation

🚀 [Download MySQL](https://dev.mysql.com/downloads/installer/) 🚀

Your MySQL adventure begins here! Click the link above to initiate the MySQL download.

**But hold on, there's more!** We'll be your guides throughout the installation process, ensuring a seamless setup. Dive in and let's embark on this exciting voyage of mastering MySQL with Python!


### **Step 1: Choose Your Flavor**

Visit the official MySQL website and download the Community Server Edition tailored to your operating system, such as Windows.

### **Step 2: Select Your Version**

You have two options for downloading the setup:
- **mysql-installer-web-community** (if you have a good internet connection)
- **mysql-installer-community** (for slower connections)

Choose the one that suits your needs.

![Download Options](https://user-images.githubusercontent.com/63813881/173280356-9ca94e07-5ddf-4a40-92c3-253f396c79b7.png)

### **Step 3: Unleash the Installer**

Once the setup is downloaded, unzip it and run the MSI installer (.exe file). It will open up the installer wizard.

![Installer Wizard](https://user-images.githubusercontent.com/63813881/173280339-f7c8b98a-f97c-4e8b-b2f5-dac12d692281.png)

### **Step 4: Choose Your Destiny**

Select the **Full** installation option in the wizard. This choice installs a comprehensive set of MySQL components, including MySQL Server, MySQL Shell, MySQL Router, MySQL Workbench, MySQL Connectors, documentation, samples, examples, and more.

![Full Installation](https://user-images.githubusercontent.com/63813881/173280369-fcea302e-f300-4149-b480-4208362ef840.png)

### **Step 5: Handle Dependencies**

The wizard may detect some missing requirements. You can resolve this by clicking **Execute**, which will install all necessary dependencies automatically. Alternatively, you can choose to skip them and proceed. Click **Next** when ready.

![Resolve Dependencies](https://user-images.githubusercontent.com/63813881/173280402-a988a5dc-f091-4449-b143-cdaf7423d160.png)

### **Step 6: Confirm and Continue**

You'll be prompted to confirm your choices for installation. Click **Yes** to proceed.

![Confirm Installation](https://user-images.githubusercontent.com/63813881/173280408-344e2c75-b3f8-4aa1-b73a-bd2665baa547.png)

### **Step 7: Server Configuration**

Now, it's time to configure the MySQL Server. Choose **Standalone MySQL Server/Classic MySQL Replication** and click **Next**. You can also opt for InnoDB Cluster if it suits your needs.

![Server Configuration](https://user-images.githubusercontent.com/63813881/173280466-8e31e5ae-bd7e-44ac-8a56-374c0e41a883.png)

### **Step 8: Configuration Details**

Select **Development Machine** as the **Config Type** and choose **TCP/IP** for connectivity. Set the **Port Number** to 3306. Then, click **Next**.

![Configuration Details](https://user-images.githubusercontent.com/63813881/173280473-8acf6d90-3cbe-4e45-8428-7f6f5fafaeea.png)

### **Step 9: Authentication Method**

Choose your preferred authentication method and click **Next**. The first option is a common choice.

![Authentication Method](https://user-images.githubusercontent.com/63813881/173280492-bdbca34b-d172-4813-b865-2adf60d8f2ae.png)

### **Step 10: Set the Root Password**

Enter and confirm your MySQL Root Password, then click **Next**.

![Set Root Password](https://user-images.githubusercontent.com/63813881/173280511-5bdf705a-96f4-483d-8516-969864cd8976.png)

### **Step 11: Windows Service Configuration**

Keep the default settings for configuring the Windows Service. Click **Next**.

![Windows Service Configuration](https://user-images.githubusercontent.com/63813881/173280530-c078626b-0b6c-4c8f-94dc-13d69a13f578.png)

### **Step 12: Execute Server Configuration**

If you're satisfied with the server configuration, click **Execute** to proceed.

![Execute Configuration](https://user-images.githubusercontent.com/63813881/173280548-c22abf24-54c7-4dac-82af-a08c3e0bf5e9.png)

### **Step 13: Configuration Complete**

Once the configuration is complete, you'll see the following screen. Click **Finish**.

![Configuration Complete](https://user-images.githubusercontent.com/63813881/173280555-175ceb56-f710-463f-992b-ed3524f6516f.png)

### **Step 14: Product Configuration**

In the next screen, you'll find that the Product Configuration is completed. Stick with the default settings and click **Next** ➔ **Finish** to finalize the MySQL package installation.

![Product Configuration](https://user-images.githubusercontent.com/63813881/173280581-7bdbe189-77ce-4ebc-bb78-c44d545d2d2e.png)

### **Step 15: Configure the Router (Optional)**

If you wish to configure the Router, click **Next** ➔ **Finish** and then hit **Next**.
![image](https://user-images.githubusercontent.com/63813881/173280593-d5933d29-61a4-432b-aac4-44a51257abd6.png)

### **Step 16: Connect to Server**
In the next wizard, we will see the Connect to Server option. Here, we have to mention the root password, which we had set in the previous steps.
![image](https://user-images.githubusercontent.com/63813881/173280603-1563352a-c972-4230-a624-36f2259ccdb8.png)
In this screen, it is also required to check about the connection is successful or not by clicking on the Check button. If the connection is successful, click on the Execute button. Now, the configuration is complete, click on Next.

### **Step 17: Execute Applied Configurations**
In the next wizard, select the applied configurations and click on the Execute button.
![image](https://user-images.githubusercontent.com/63813881/173280619-90407455-8fcd-4bb5-b2c7-ca341fc5f79c.png)

### **Step 18: Finish Strong**
After completing the above step, we will get the following screen. Here, click on the Finish button.
![image](https://user-images.githubusercontent.com/63813881/173280630-1760437d-11be-4704-a868-c1c4d9b7c96a.png)

### **Step 19: MySQL Installation Complete**
Now, the MySQL installation is complete. Click on the Finish button.
![image](https://user-images.githubusercontent.com/63813881/173280646-5f4cf713-ab86-40a8-a4b5-658bfa5462b8.png)

## Verify MySQL installation
Once MySQL has been successfully installed, the base tables have been initialized, and the server has been started, you can verify its working via some simple tests.

Open your MySQL Command Line Client; it should have appeared with a mysql> prompt. If you have set any password, write your password here. Now, you are connected to the MySQL server, and you can execute all the SQL command at mysql> prompt as follows.

**For example:** Check the already created databases with show databases command:
![image](https://user-images.githubusercontent.com/63813881/173280683-4ac11109-c2fa-4087-a6a5-8782b959f179.png)

## Install Library in Python

To interact with MySQL in Python, you'll need to install the necessary libraries:
1. `pip install mysql`
2. `pip install mysql.connector`
3. `pip install mysql-connector-python`

Enjoy your MySQL journey!
