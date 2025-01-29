<p align="center">
<img src="https://www.imagar.com/wp-content/uploads/2018/06/azure.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>How to Setup a Subscription and a Resource in Azure</h1>
This is online tutorial on how to setup an subscription and resources in Azure. Creating a resources in Azure will allow beginners to practice and learn how to use Azure through labs to gain experience with the application.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Steps</h2>

 -Step 1: Create an Azure account and open the Azure portal
 
 -Step 2: Create a Resource group within the Azure portal
 
 -Step 3: Create a storage account within the resource group created
 
 -Step 4: Create a file on your desktop and upload it into the storage account
 
 -Step 5: Edit the file created in the last step within the portal
 
 -Step 6: Download file and observe the changes made
 
 -Step 7: Delete the resource group so that you do not incur charges
 
 -Step 8: Verify that the resource is deleted


<h2>Azure Setup Steps and Resource Group Creation</h2>

![Screenshot 2025-01-28 202410](https://github.com/user-attachments/assets/3671f24d-be7e-4d7c-b526-df96557a5fe5)

<p>
First, you will need to create an Azure account. Go to https://azure.microsoft.com/en-us/free/ and click the green start free button. This step will require a credit/debit card, but it will not be charged.
</p>
<br />

![Screenshot 2025-01-28 202943](https://github.com/user-attachments/assets/13aadc4f-6c83-4cf2-89ee-76ca169b51eb)

<p>
After the account is made, you will need to go to https://portal.azure.com. From here, you will sign into the portal with the email and password that you created in the previous step. Inside the portal you will type "Subscriptions' and click the gold key to ensure that your subscription is currently active. After this, we will create a resource group.
</p>
<br />

![Screenshot 2025-01-28 203239](https://github.com/user-attachments/assets/be32fc9a-225a-43c4-a762-0c2133f5d59d)

<p>
Navigate to resource groups by typing it into the search bar. From there press the blue button that says "Create resource group".
</p>
<br />

![Screenshot 2025-01-28 203522](https://github.com/user-attachments/assets/de31cd3a-fc89-4c8a-aefb-dd8e335bb3e2)

<p>
We will finally start configuring our resource group. You will most likely only have one subscription so it will already be defaulted onto the one you have created. We will only be creating the name and changing the region. For the name of the group, we can name it "RG-1". You can change this to whatever you would like, but this is the sample name we will be using. Next, you will set the region to whatever is closest to you by pressing the dropdown menu. We will be using "West US 3" for this tutorial. Review + create >" on the bottom left after you have finished.
</p>

![Screenshot 2025-01-28 203652](https://github.com/user-attachments/assets/6622fb34-bf1c-4e0f-8dc4-6a84c201127e)

<p>
This last page will be where you confirm everything is correct and press "Create" on the bottom left to finalize the creation of the resource group.
</p>
<br />

![Screenshot 2025-01-28 203900](https://github.com/user-attachments/assets/b95c45f0-526c-405a-a0e7-66c4f7a662f5)

<p>
We will now check to see if the resource group that we created is active by going back to the Resource Group page by typing it into the search bar once again. Next we will be testing the resource group by creating a Azure Storage Account which is like a Google Drive or iCloud for apple.
</p>
<br />

![Screenshot 2025-01-28 204001](https://github.com/user-attachments/assets/7d9a5148-bc3b-498f-b588-ef66f7e65354)

![Screenshot 2025-01-28 204056](https://github.com/user-attachments/assets/f005e338-ea25-448c-b155-e18f70b98cc9)

<p>
Create a storage account by typing "Storage Account" in the search bar and pressing the button in the service section. Once there, press the "Create storage account" button.
</p>
<br />

![Screenshot 2025-01-28 204707](https://github.com/user-attachments/assets/69d5f4b0-6bb0-49d2-ad81-fc171f773692)

![Screenshot 2025-01-28 204741](https://github.com/user-attachments/assets/622b71c0-eb44-4076-8357-a75cf598b148)

<p>
Next we will make sure the subscription and resource group is selected to the one we just created. If not, select it by pressing the drop down menu for both. From there, you'll need to make a unique name for the account and confirm that the account is in the same region as your resource group. You will then hit the blue review button on the bottom left to run the validation. Lastly, you will hit create. 
</p>
<br />

![Screenshot 2025-01-28 204858](https://github.com/user-attachments/assets/50309934-68dd-4513-b283-b92612913788)

<p>
Wait for it to complete deployment and hit "Go to resource".
</p>
<br />

![Screenshot 2025-01-28 205001](https://github.com/user-attachments/assets/7c31d0ab-aab0-4554-ac7c-3ea012889533)

<p>
Once you are in the storage account, click on containers.
</p>
<br />

![Screenshot 2025-01-28 205532](https://github.com/user-attachments/assets/ea315b35-b3d2-46c3-99bb-e3fccd49fde5)

<p>
Now create a new container, name it, and hit create.
</p>
<br />

<p>
<img src="https://imgur.com/3pl9aY3.png"/>
</p>
<p>
Now click on the new container you just made, and we are going to upload a basic text file into the container.
</p>
<br />

<p>
<img src="https://imgur.com/w7sOZVz.png"/>
</p>
<p>
Just make a new text document on your desktop, then name it and write what ever you want in it.
</p>
<br />

<p>
<img src="https://i.imgur.com/1nutBNY.png"/>
</p>
<p>
Click the upload button and you can just drag and drop the file from your desktop or you can search for it in file explorer, and then upload it!
</p>
<br />

<p>
<img src="https://i.imgur.com/TIOrw9I.png"/>
</p>
<p>
Now that you have uploaded the file, you can edit, download it to your computer, or do whatever you want with it.
</p>
<br />

<p>
</p>
<p>
That is the last step of creating a storage account. Now we will delete the resource group to make sure you don't incur a charge. Once deleted you will need to remake the resource group, but you can do this as many times as you like to practice.
</p>
<br />

<p>
<img src="https://i.imgur.com/TZXjAuP.png"/>
</p>
<p>
To delete the resource group, just go back to the resource groups page, click on the resource group, click delete resource group, and type/copy paste the resource group's name to confirm, and then click delete.
