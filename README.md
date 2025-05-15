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
![Azure Portal](https://github.com/user-attachments/assets/d11d174b-3cef-44b7-bdfc-b0d929b6b59a)

 
After creating an account, follow the step-by-step list to gain an understanding of what to do in Microsoft Azure.
1.	Within the Azure Portal, Create a Resource Group
![Resource Groups - Create New](https://github.com/user-attachments/assets/5e4a5de5-0ca7-4c9d-b77b-a4fe60ae3025)
 
Go to Resource Groups on the Azure page and click “Create New”
![Create Resource Group](https://github.com/user-attachments/assets/85b5f79b-4307-40d2-8e6b-a0bf079d7a0c)
 
After clicking Create New, be sure to have the Resource Group within the Azure subscription of your choice. Create a name for the Resource Group and make sure it wasn’t used before as every RG has a unique name. In this example, the RG name is “CCLab1KP. After creating a name, select a region of your choosing (Ex. East US).
Once the Resource Group is created, you can access the RG within Azure using this directory:
![Resource Groups Directory](https://github.com/user-attachments/assets/cb7a7eab-5e88-4662-ad5c-5d14ce7937bb)
 

2.	Create a Storage Account within the Resource Group created in Step 1
 
Within Azure, go to Storage Accounts and click “Create Storage Account.”
 
After clicking “Create Storage Account”, be sure to have the Storage Account within the Resource Group of your own choice. In addition, make sure the Storage Account name is given a unique name as well as the region you want to associate it with. After that, click “Review + create” if there are no additional settings you want to add.
 
After your Storage Account has been created, you can access it within the Azure directory at any time.
3.	Create a file on your local desktop and upload it to the Storage Account
After creating a text file on your local desktop, go to the Storage Account and click Upload. You should see a screen that says “Upload Blob”:
 
From there, click “Browse for Files” and insert the text file you created into the Upload Blob:
 
Be sure to name the container as seen in the image above, as well as the example below:
 
Once the file has been uploaded to the Storage Account, you can access the file within this directory: HomeStorage Account (name of storage account) Data Storage Containers
 

4.	Edit the file within the Storage Account (within the Azure Portal)
To access the file in the Azure Portal, go to the Storage Account that was created and go to the Containers section and click on the name of the container that was created. In this case, it was “text”:
 
From there, click the text file “CCLab01.txt” and then click Edit. You should see a code format as shown below:
 
Within that blob, you can edit the text to what you want to type in. Here is an example of what was typed after:
 
Save the file to avoid losing changes

5.	Download the file and observe the changes
 
Here is an example of the text file downloaded from Azure after editing the file. You can do this with any file that’s uploaded within the storage container.
6.	Delete the Resource Group created in step 1 (in order to ensure you don’t incur “cost”)
 
This is the most important part of Microsoft Azure since once your Resource Group is no longer needed within your project, be sure to click on the Resource Group created in the directory and then click “Delete Resource Group”. This is absolutely important since you don’t want to incur charges as cloud storage services cost a fee.
7.	Verify that the Resource Group has been deleted
 
Once you click Delete Resource Group, type in the name of the RG for verification and click Delete. From there, check the notifications in Azure to ensure the Resource Group is successfully deleted.

<br />
