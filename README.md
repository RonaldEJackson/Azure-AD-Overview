<p align="center">
<img src="https://imgur.com/bUuL616.png alt="Traffic Examination"/>  
</p>
<br />
<br />

<h2>Azure Active Directory Overview (User & Group Creation/Access Management Configuration</h2>

In this tutorial I demonstrate Azure Active Directory user account creation, group creation and access management configuration.


<h2>Environments and Technologies Used</h2>

- Microsoft Azure Cloud Platform


<h2>Resources Used </h2>

- Azure Resource Groups
- Access Control (IAM)


<h2>Video Demonstrations</h2>

Click below for Video Demonstrations:
 
 <details close>

<div>

</summary>

1. Configure and Observe Tenant-Level Global Reader

   - Create a user within Azure Active Directory (AAD) (username: globalreaderjohn)
   - Assign Tenant-Level Global Reader
   - In a new browser/incognito, log in as globalreaderjohn and observe result of being a Tenant Level “Global Reader” (Users, Active Directory)
   - Close browser/incognito when satisfied
   
   
   [![Part 1](https://i.vimeocdn.com/video/1650062289-7ccc552d70b43340cca69ae434e376aa8f955e319d47e0fecf7aada8277bf8fd-d_295x166?r=pad)](https://vimeo.com/814446209 "Azure AD Lab Part 1")
   <br />
   <br />
   
   
2. Configure and Observer Subscription Reader
    - Back in main browser, create another user within AAD  (username: subreaderjane)
    - Assign Subscription-Level Reader 
    - In a new browser/incognito, log in as subreaderjane and observe result of being a Subscription Level “Global Reader” (Subscriptions, Resource Groups) 
    - Close browser/incognito when satisfied
    
   [![Part 2](https://i.vimeocdn.com/video/1650062530-df7c05e5d4d7947027ec4343beb30337a184bbca53d1776856bfb94d7c29efd3-d_295x166?r=pad)](https://vimeo.com/814445455 "Azure AD Lab Part 2")
   <br />
   <br /> 
   
   
 3. Configure and Observe Resource Group Contributor (like an admin)
    - Back in main browser, create another user within AAD  (username: rgcontributordave)
    - Create a new resource group called “Permissions-Tester”
    - Assign Resource Group-level Contributor and  Subscription Level Reader
    - For our resource group “Permissions-Tester” assign Contributor Permissions
    - In a new browser/incognito, log in as rgcontributordave and observe result of being a Subscription Level Reader and Resource Group-level Contributor
    - Observe the result of being a Resource Group Level Contributor (Storage Account Creation)
    
    
   [![Part 3](https://i.vimeocdn.com/video/1650062688-f002defe9163278411c198fc03cde5436e68fad140f57c2b66cfed3eb049118f-d_295x166?r=pad)](https://vimeo.com/814445527 "Azure AD Lab Part 3")
   <br />
   <br />   
   
   
This is the end of the tutorial. I hope it helped you out!
    
   
   
 
   
   
   
   
   
   
   
   
   
   
   
   
