# Creating and Deploying a Web Application on Azure
<p align="center">
Web App Example: <br/>
<img src="https://i.imgur.com/hqsmmpX.png" height="80%" width="80%" alt="Create a Resource"/>

<br />

<img src="https://i.imgur.com/Aj4fbIq.png" height="80%" width="80%" alt="Create a Resource"/>

<br />
<br />
<h2>Description</h2>
This Project will demonstrate the steps on how to Deploy a Web App utilizing Microsoft Azure services.

<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 
- <b>Microsoft Azure services</b>

<h2>Environments Used </h2>

- <b>Mac OS</b>

<h2>Project Guide:</h2>  

1. Sign up for an account on Microsoft Azure portal.azure.com



2. You have to establish a Resource Group, this step is necessary as the web application requires a subscription service to be deployed. 

<p align="center">
Creating Resource Group: <br/>
<img src="https://i.imgur.com/YJ8gaVh.png" height="80%" width="80%" alt="Create a Resource"/>

<br />
<br />


3. Navigate to Azure search field and search and select "App Services"

<p align="center">
<br/>
<img src="https://i.imgur.com/LuhCcg6.png" height="80%" width="80%" alt="appservices"/>

<br />
<br />



4. Select "+ create" to start creation of Application

<p align="center">
 <br/>
<img src="https://i.imgur.com/ZkYUp8I.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />




5. In the "Basics" tab select the following:

-Subscription/Resource Group: Select the Resource group that was created is Step 1.

-Name: Whichever name you create will be the name for the Web app I decided on "Davidcyberblog"

-Publish: Select "Code."

-Runtime Stack: Select "PHP 8.2"

-Operating System: Select "Linux."

-Region: Select the same region that was used for the resource group.

<br/>

<p align="center">
The following image shows the completed "Basics" tab: <br/>
<img src="https://i.imgur.com/tk6Y9il.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />


6. Normally this step is where you would create your App Service Plan by:


-Under "Linux Plan," select "Create New" and then enter any name for your project plan

-Under "Sku and size," select "Change size."

-The spec picker will pop up on the right-hand side of your screen.
(This allows you to choose the pricing structure of your web app.)

-Select "Dev/Test" and "Plan B1" (the green option), and then click "Apply," 

(In my example I selected the completely free tier so I could not customize these options, the more you are willing to pay the more space and bandwidth will be allowed for your application)


<p align="center">
Example: <br/>
<img src="https://i.imgur.com/agGvXUv.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />


7. You can leave all other options is other tabs as default. Select the "Review + Create" tab.


<p align="center">
<br/>
<img src="https://i.imgur.com/tk6Y9il.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />

8. Select "Create" at the bottom
   
<p align="center">
<br/>
<img src="https://i.imgur.com/ydowDy9.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />


9. Once App has been created and deployed you will be able to find it by clicking "Go to Resource" , or searching "App Services" in the Azure search field.
Application Page: <br/>
<img src="https://i.imgur.com/HHsWStq.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />




























<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
