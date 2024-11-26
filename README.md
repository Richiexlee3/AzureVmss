<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory Deployed in the Cloud (Azure)</h1>
Let’s build an Active Directory (AD) network in Azure! This will help you manage users, computers, and permissions—just like real IT admins do. Follow these steps, and you’ll have your AD up and running in no time.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Get Started with Azure
- Step 2: Log in to the Azure Portal
- Step 3: Observe the portal
- Step 4: Create a Resource Group
- Step 5: Create a Storage Account
- Step 6: Create and Upload a Text File
- Step 7: Edit the File in Azure
- Step 8: Download and View the File
- step 9: Clean Up to Avoid Costs
- Step 10: Verify and Check Costs
- Important Reminder
Always delete unused resources to avoid extra charges.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/BF63nwy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Create a Free Subscription

Go to: Azure Free Account.

Click Start Free and sign in with your Microsoft account. 

Don’t have one? Create it—it’s quick and free!

Fill in your details (name, address, etc.) and add a payment method.

Submit to activate your account.

Alternatively, you can choose Pay As You Go for flexible billing.
</p>
<br />

<p>
<img src="https://i.imgur.com/QQDO6Sn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Log in to the Azure Portal

Go to: Azure Portal.

Log in with your account to access your Azure dashboard.
</p>

Step 3: Explore the Portal

Use the search bar at the top of the page to explore these key features: 

"Resource Groups": Manage your resource containers.

"Virtual Machines": Manage cloud computers. 

"Cost Management": Track spending.

</p>
<br />
<p>
<img src="https://i.imgur.com/3oBVEoo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: Create a Resource Group

Search "Resource Groups" in the search bar and select it.
<p>
<img src="https://i.imgur.com/qLnmg1c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Click Create.
<p>
<img src="https://i.imgur.com/19DxD0N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fill in: 

Name: MyResourceGroup

Region: Choose one close to you (e.g., East US).

<p>
<img src="https://i.imgur.com/gwD6G4f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Click Review + Create, then Create.

</p>
<br />
<img src="https://i.imgur.com/FDc8ald.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5: Create a Storage Account

Search "Storage Accounts" in the search bar and select it.
</p>
<br />
<img src="https://i.imgur.com/4jeOsFp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Create.
</p>
<br />
<img src="https://i.imgur.com/Ku1kWxM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fill in: 

Resource Group: Select MyResourceGroup.

Storage Account Name: MyStorage123 (choose a unique name).

Region: Same as your Resource Group.

</p>
<br />
<img src="https://i.imgur.com/1RJkf6N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Click Review + Create, then Create.

</p>
<br />
<img src="https://i.imgur.com/EkY5Rhq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6: Create and Upload a Text File

On your computer, create a file:

Open Notepad (Windows) or TextEdit (Mac).

Type: Hello, Azure!

Save it as MyFirstFile.txt.

If you’re on Mac, go to preferences and set the file to Plain Text.

</p>
<br />
<img src="https://i.imgur.com/LMZlBPJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

In Azure:

Search "Storage Accounts" and click your storage account.

</p>
<br />
<img src="https://i.imgur.com/lzqXLd5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Click Containers, create a container (e.g., mycontainer), and open it.

</p>
<br />
<img src="https://i.imgur.com/XoJNQik.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Click Upload 

</p>
<br />
<img src="https://i.imgur.com/ZePybnT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

select your MyFirstFile.txt file.

</p>
<br />
<img src="https://i.imgur.com/HMKb7s1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7: Edit the File in Azure

</p>
<br />
<img src="https://i.imgur.com/XwSHVyB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Inside the container, click your file (MyFirstFile.txt).

Click Edit, add another line (e.g., Edited in Azure!), and save it.

</p>
<br />
<img src="https://i.imgur.com/5m2Ak6A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8: Download and View the File

Inside the container, click your file and select Download.

</p>
<br />
<img src="https://i.imgur.com/8fGP1jw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open it on your computer to see the changes!
</p>
<br />
<img src="https://i.imgur.com/7x9QGAw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 9: Clean Up to Avoid Costs

Search "Resource Groups" in the search bar and select your resource group.
</p>
<br />
<img src="https://i.imgur.com/5BdI9Xa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Delete Resource Group to remove everything inside it. 

</p>
<br />
<img src="https://i.imgur.com/ZiFhIqR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Type the name of the Resource Group to confirm deletion.

</p>
<br />
<img src="https://i.imgur.com/csmTomW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 10: Verify and Check Costs

Search "Cost Management" in the search bar and select it.

</p>
<br />
<img src="https://i.imgur.com/7okj1VQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Go to Cost Analysis to confirm there are no unexpected charges.

Important Reminder

Always delete unused resources to avoid extra charges.

🎉 Congratulations! You’ve successfully used Azure step by step. You’re now ready to build bigger and better projects in the cloud. 🚀
</p>
<br />
