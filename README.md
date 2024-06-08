<p align="center">
<img src="https://i.imgur.com/Us74xWW.png" height="40%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Create an Azure Account and Deploy a Virtual Machine</h1>
Microsoft Azure is a cloud computing platform with various products and services. In this guide, I will teach you how to create an account, utilize the portal, and create a virtual machine.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Microsoft Remote Desktop (macOS) for virtual machines

<h2>Configuration Steps</h2>

- Step 1: Create Azure Account
- Step 2: Azure portal and resource group
- Step 3: Create a virtual machine
- Step 4: Connect to virtual machine using Microsoft Remote Desktop on macOS

<h3>Step 1: Create Azure Account</h3>
The very first step is to create an Azure account. You can create an account with $200 of free credit for a month. 

<br>
<br>

Create an Azure account [here](https://azure.microsoft.com/en-us/free/).

<p align="center">
<img src="https://i.imgur.com/8NgUUZu.png" height="80%" width="80%" alt="Azure Free Account"/>
  
<p align="center">
<img src="https://i.imgur.com/mSLAKSQ.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>

Follow all the steps above to create the account. A credit card will be needed but will not be charged unless you upgrade the subscription after a month's use. After you create your account, you are now allowed to use Azure.

<h3>Step 2: Azure portal and resource groups</h3>

Now that the account has been created, we can navigate to the Azure portal. The portal is where you can find all the products/resources and manage your subscriptions.

The portal is located [here](https://www.portal.azure.com).

<p align="center">
<img src="https://i.imgur.com/8JnxniW.png" height="80%" width="80%" alt="Azure Portal with RG Arrow"/>
</p>

A Resource Groups needs to be created in order to use some of the services in Azure. Resource Groups store all resources that you are utilizing in Azure. This example will show how to deploy a Windows 10 virtual machine.

<p align="center">
<img src="https://i.imgur.com/x5P8pDQ.png" height="80%" width="80%" alt="Azure Resource Groups with circle"/>
</p>

After you click created Resouce Groups, you will need to name your Resource Group and select the region. The region will determine which Azure data center will be used. In this example, I chose (US) West 3. Click "Review + Create" when finished.

<p align="center">
<img src="https://i.imgur.com/4ZY0Twp.png" height="80%" width="80%" alt="Create Azure Resource Groups"/>
</p>

<h3>Step 3: Create a virtual machine</h3>
The next step is to create a VM or "Virtual Machine." At the portal, click on VM and click create. Once at the create VM menu, follow all the instructions. Make sure you fill out all the areas that have a red asterisk on them (Resource Group, Name, etc.). Disregard the other tabs such as disks and networking because they are not needed. Make sure you remember the username and password you created! Once this is all completed, your VM will appear in your Resource Group.

<p align="center">
<img src="https://i.imgur.com/XC53r2o.png" height="80%" width="80%" alt="Virtual Machine Menu with arrow"/>
</p>

<p align="center">
<img src="https://i.imgur.com/a0OIYax.png" height="80%" width="80%" alt="Create Virtual Machine"/>
</p>

<h3>Step 4: Connect to VM using Microsoft Remote Desktop on macOS</h3>
The final step to this process is accessing the VM using Microsoft Remote Desktop. I am using a macOS, so I will have to download the application in the App Store. 

<p align="center">
<img src="https://i.imgur.com/pp1yQTE.png" height="80%" width="80%" alt="Microsoft Remote Desktop"/>
</p>

In order to connect to the VM, first you need the public IP address, which is found on the right side of the menu.

<p align="center">
<img src="https://i.imgur.com/gT6F62H.png" height="80%" width="80%" alt="SampleVM menu with arrow and circle"/>
</p>

Once Microsoft Remote Desktop is downloaded, open the application. Click add PC. Copy and paste the public IP Address of the VM that was created when prompted. Type in the username and password, and then click connect. 

<p align="center">
<img src="https://i.imgur.com/WcRdlX3.png" height="80%" width="80%" alt="Microsoft Remote Desktop 1"/>
</p>

<p align="center">
<img src="https://i.imgur.com/4IKJFik.png" height="80%" width="80%" alt="Windows 10 VM"/>
</p>

Great! Now you have created your first Virtual Machine within Azure. Make sure you delete all of your Resource Groups in order maximize your free month worth of $200 credits. Thank you!

