<p align="center">
<img src= https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/640px-Microsoft_Azure_Logo.svg.png alt="Azure Logo"/>
</p>

<h1>Understanding the Basics of Microsoft Azure</h1>
In this tutorial, we learn the basics of understanding Microsoft Azure by creating a subscription and creating simple exercises <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Step 1: Creating a Microsoft Azure account
- Step 2: Subscribing to a traditional Azure subscription or Pay-As-You-Go

<h2>Actions and Observations</h2>
To gain skills in IT, one must know about cloud services such as Amazon Web Services, Microsoft Azure, etc. In this case, we will explain how to gain a basic understanding of Microsoft Azure as well as what to do with an Azure subscription. Before using Azure, be sure to create an account and pick a traditional Azure subscription or a “Pay-As-You-Go” option. Once that is created, this is what the home screen of Microsoft Azure will look like:

![Azure Portal](https://github.com/user-attachments/assets/9e76b5a2-f343-4b05-a0f2-dd441a40adad)

 
After creating an account, follow the step-by-step list to gain an understanding of what to do in Microsoft Azure.
1.	Within the Azure Portal, Create a Resource Group

![Resource Groups - Create New](https://github.com/user-attachments/assets/5e4a5de5-0ca7-4c9d-b77b-a4fe60ae3025)
 
Go to Resource Groups on the Azure page and click “Create New”

![Create Resource Group](https://github.com/user-attachments/assets/85b5f79b-4307-40d2-8e6b-a0bf079d7a0c)
 
After clicking Create New, be sure to have the Resource Group within the Azure subscription of your choice. Create a name for the Resource Group and make sure it wasn’t used before as every RG has a unique name. In this example, the RG name is “CCLab1KP. After creating a name, select a region of your choosing (Ex. East US).
Once the Resource Group is created, you can access the RG within Azure using this directory:

![Resource Groups Directory](https://github.com/user-attachments/assets/cb7a7eab-5e88-4662-ad5c-5d14ce7937bb)
 

2.	Create a Storage Account within the Resource Group created in Step 1

![Storage Accounts - Create New](https://github.com/user-attachments/assets/7d49d07a-cd67-414e-9cec-92ecaf5b29da)
 
Within Azure, go to Storage Accounts and click “Create Storage Account.”

![Create Storage Account](https://github.com/user-attachments/assets/97bffdab-8976-40b7-881b-8e2c48f9e2f3)
 
After clicking “Create Storage Account”, be sure to have the Storage Account within the Resource Group of your own choice. In addition, make sure the Storage Account name is given a unique name as well as the region you want to associate it with. After that, click “Review + create” if there are no additional settings you want to add.

![Storage Account Directory](https://github.com/user-attachments/assets/ec26f8ad-35d4-4487-bc1a-a017fa804e94)
 
After your Storage Account has been created, you can access it within the Azure directory at any time.
3.	Create a file on your local desktop and upload it to the Storage Account
After creating a text file on your local desktop, go to the Storage Account and click Upload. You should see a screen that says “Upload Blob”:

![Upload Blob](https://github.com/user-attachments/assets/3690b743-1cb7-413f-a2b2-b088984b95b6)
 
From there, click “Browse for Files” and insert the text file you created into the Upload Blob:

![Upload Blob - with file](https://github.com/user-attachments/assets/3c47e3cc-0762-4fc9-9389-0886c2db1746)
 
Be sure to name the container as seen in the image above, as well as the example below:

![Upload Blob - create new container](https://github.com/user-attachments/assets/0790331b-a63c-407f-bf35-11e74854461f)
 
Once the file has been uploaded to the Storage Account, you can access the file within this directory: Home-->Storage Account--> (name of storage account)--> Data Storage--> Containers

![Storage Account - Data Storage- Containers](https://github.com/user-attachments/assets/059a864d-84c1-4acf-b394-1658fca787b7)
 

4.	Edit the file within the Storage Account (within the Azure Portal)
To access the file in the Azure Portal, go to the Storage Account that was created and go to the Containers section, and click on the name of the container that was created. In this case, it was “text”:

![Storage Account - Data Storage- Containers](https://github.com/user-attachments/assets/c95245b4-95b1-4ec8-9ed4-d4311091a6f3)
 
From there, click the text file “CCLab01.txt” and then click Edit. You should see a code format as shown below:

![Container - Edit Text](https://github.com/user-attachments/assets/c59410cd-4cde-467d-a09e-2d681c1d29ea)
 
Within that blob, you can edit the text to what you want to type in. Here is an example of what was typed after:

![Container - Edit Text Post](https://github.com/user-attachments/assets/d48d0e91-e925-4799-b9f3-7e79cb106fb3)
 
Save the file to avoid losing changes

5.	Download the file and observe the changes
 
Here is an example of the text file downloaded from Azure after editing the file. You can do this with any file that’s uploaded within the storage container.

![Text File after edit on Azure](https://github.com/user-attachments/assets/3badc70e-b5ca-44ea-9d9b-aeb476243e24)

6.	Delete the Resource Group created in step 1 (to ensure you don’t incur “cost”)

![Delete Resource Group after completion of Lab 1](https://github.com/user-attachments/assets/f4b753e3-d971-4295-851d-e16f65a69372)
 
This is the most important part of Microsoft Azure, since once your Resource Group is no longer needed within your project, be sure to click on the Resource Group created in the directory and then click “Delete Resource Group”. This is important since you don’t want to incur charges, as cloud storage services cost a fee.
7.	Verify that the Resource Group has been deleted

![Delete Resource Group - confirm delete](https://github.com/user-attachments/assets/4fcdef6b-211f-4658-8540-a0eb703bdb39)
 
Once you click Delete Resource Group, type in the name of the RG for verification and click Delete. From there, check the notifications in Azure to ensure the Resource Group is successfully deleted.

<br />
