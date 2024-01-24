# Deploying a Web Application
<br />
<h2>Description</h2>
This Project will demonstrate the steps on how to Deploy a Web App utilizing Microsoft Azure services.

<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 
- <b>Microsoft Azure services</b>

<h2>Environments Used </h2>

- <b>Mac OS</b>

<h2>Project walk-through:</h2>  

1. Sign up for an account on Microsoft Azure portal.azure.com



2. You have to establish a Resource Group, this step is necessary as the web application requires a subscription service to be deployed. 

<p align="center">
Creating Resource Group: <br/>
<img src="https://i.imgur.com/YJ8gaVh.png" height="80%" width="80%" alt="Create a Resource"/>

<br />
<br />


3. Navigate to Azure search field and search and select "App Services"

<p align="center">
Generating SSH Key: <br/>
<img src="https://i.imgur.com/kyMKdGE.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />



4. Select "+ create" to start creation of Application

<p align="center">
Jumpbox Creation: <br/>
<img src="https://i.imgur.com/8AQhVyA.png" height="80%" width="80%" alt="SSH"/>

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
The following image shows the completed "Basics" tab:

<p align="center">
Server Creation: <br/>
<img src="https://i.imgur.com/4NkFxJz.png" height="80%" width="80%" alt="SSH"/>

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
SSH Security Rule: <br/>
<img src="https://i.imgur.com/9grLrCz.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />


7. You can leave all other options is other tabs as default. Select the "Review + Create" tab.


<p align="center">
Install Docker: <br/>
<img src="https://i.imgur.com/vfN5yKw.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />

8. Select "Create" at the bottom
   
<p align="center">
Pulling Container: <br/>
<img src="https://i.imgur.com/QnnWfZL.png" height="80%" width="80%" alt="SSH"/>

<br />
<br />


9. Once App has been created and deployed you will be able to find it by clicking "Go to Resource" , or searching "App Services" in the Azure search field.

<p align="center">
Running container: <br/>
<img src="https://i.imgur.com/fkQgAVO.png" height="80%" width="80%" alt="SSH"/>

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
