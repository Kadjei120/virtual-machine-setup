<p align="center">

  <img src="https://i.imgur.com/7Ny2zah.png" alt="Azure logo" width="200" />
</p>

<p align="center">
  <b>Microsoft Azure Integration</b><br/>
  Seamlessly integrate your app with Azure services for enhanced scalability and performance.
</p>

</p>

<h1>Azure - Virtual Machine Creation </h1>
This tutorial outlines the creation of a virtual machine on the cloud computing platform Microsoft Azure .<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Windows 10
- Azure Virtual Machines
- Azure Resource Groups

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2)

<h2>List of Prerequisites</h2>

- ✅ Azure Subscription: You need an active Azure account with a valid subscription to create and manage resources.
- ✅ Resource Group: Create a new resource group to logically group your VM and related resources.
- ✅ Virtual Machine: Create a virtual machine, implementing the correct features

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/IS5yIti.png" height="80%" width="80%" alt="Azure Home Page"/>
</p>
<p>
 
So you can go ahead and get logged into your Azure account. Once you are logged in, you will automatically land on the Azure home page. You then want to click on "Resource Groups" as directed by the arrow in the image above. Once you have done that, you will see a blue button which says "+create" which you should click on to proceed.
</p>

<br />
<p align="center">
  <img src="https://imgur.com/xEwT5Ns.png" alt="Resource Group Creation Steps" width="500" />
</p>

<p>
Next, you want to fill these details in. For the "Subscription" please use your current subscription. For your "Resource Group Name" i recommend using the name i used, to make it easier, however feel free to make your own. Please note that you cannot use spaces, instead, use a hyphen. Next, for your "Region" i recommend using East US 2. Once all the details have been filled in, proceed by clicking "Review + Create" as directed by the arrow in the image above. Another blue button "create" will appear at the bottom, please click on this to proceed.
</p>
<br />

<p>
<img src="https://imgur.com/dnm93q6.png" height="80%" width="80%" alt="Resource Group Creation Steps"/>
</p>
<p>
You can now go ahead and refresh your page by clicking the refresh button as shown at number 1 in the image. Once the page is refreshed, you should be able to see the resource group we just created as shown at number 2 in the image. Now we can go ahead and create our virtual machine. As shown at number 3 in the image, head over to the search bar and type in "virtual machine". Next click on "virtual machine" as shown at number 4 in the image above.
</p>
<br />

<img src="https://imgur.com/J7GuqtG.png" height="80%" width="80%" alt="Resource Group Creation Steps"/>
</p>
After you clicked "Virtual Machine" you should have landed on this page. The next thing you want to do, is to click "Create" as shown at number 1 in the image above. A drop down menu should pop up, and you should then click "Azure Virtual Machine" as shown at number 2 in the image above.

<p>
<br />
<img src="https://imgur.com/4lvo5Uy.png" height="80%" width="80%" alt="Resource Group Creation Steps"/>
</p>
You should now be on this page. We can now go ahead and fill in the details for our virtual machine. For "Subscription" please use the appropriate one. For "Resource Group", use the resource group we just created as you can see at number 2 in the image above. For "Virtual Machine Name" as seen at number 3, go ahead and create a name, its perfectly fine if you use the same one as me. Once again, note that spaces arent allowed, so please use a hyphen instead. For "Region" as shown at number 4, i recommend keeping it the same as our resource group, so go ahead and choose "East US 2". For "Image" as shown at number 5, you want to go ahead and choose "Windows 10 Pro", as it is a Windows Virtual Machine that we are creating. For "Size" as seen at number 6, i recommend choosing one with 2vcpus, so go ahead and do that. After, go ahead and create a username and password as shown at number 7. Please make a note of this as you will be needing it later.

<p>
<br />
<p align="center">
<img src="https://imgur.com/Xhip9uH.png" alt="Resource Group Creation Steps" width="500" />
</p>
Next, under "Licensing" go ahead and check the box as shown in number 1 in the image above. Once all of this has been completed, go ahead and click "Review + Create" at the bottom of the page.
<p>
<p align="center">
<img src="https://imgur.com/i27RjA0.png" alt="Resource Group Creation Steps" width="500" />
</p>
Microsoft Azure will then do its final validation checks. This can take a few minutes so please wait patiently. Once the validation is successful, you can go ahead and click on "create" as shown at number 1 in the image above.
<p>
<br />
<img src="https://imgur.com/jSWc4Qr.png" height="80%" width="80%" alt="Resource Group Creation Steps"/>
</p>
The virtual machine is now in the deployment stage. Please wait for it to be deployed, as this can take up to 3mins, so please be patient. Once it has finished being deployed, you will see the message, "Your deployment is complete" as shown at number 1 in the image above. So now that our virtual machine has been created, we can now go back to our virtual machines section in Azure, by typing in the search bar, "Virtual Machine". We can now see that our virtual machine is active and showing, as shown at number 2 in the image above. Your all set! Thanks for using this tutorial, and in our next repository, we will be logging into our Virtual Machine and testing it out. (Soon to come.)
