# Privileged Identity Management - Azure AD Roles

Require Azure AD Premium P2 Licences

What is the purpose of PIM?
- Used to control privileged access to Azure resources
- IT Admins must ensure that authorized users have the required access to do their job.
- If a user leaves the department or company, PIM will ensure that their access is managed.


What services does PIM provide?
- JIT access to Azure AD and Azure Resources
- Assign <em> time-bound access </em> to resources using start and end dates
- Require approval to activate privileged roles
- Enfore MFA to activate any role
- Get notifications when privileged roles are activated
- Conduct UAR to ensure users still require the roles
- and MORE..

How do IT admins enable Privileged Identity Management (PIM)?
- IT admins will need to log in as the Global Administrator
- Consent to using PIM
- Verify identity with MFA



How to use Privileged Identity Management (PIM)?
- Important ** After assigning a Azure AD role, the user must <em> activate </em> the role assigned to them. 
- Note that IT admins can edit settings of the Azure AD role assigned to users such as limiting the time duration a user has access to a particular role or require MFA


# How to navigate to Privileged Identity Management
- Search for the service Privileged Identity Mananagement > Azure AD Roles > Assignments > Add assignments for your users

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167491136-3711bda2-d50d-4f90-a1b6-ce2e6ccb4cda.png" height="55%" width="55%" alt="Privileged Identity Management"/>
  
<p/>

- After selecting Azure AD Roles, select the Assignments blade

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167491476-2bbcc1d1-7086-431b-98ff-5d3b86d14561.png" height="80%" width="80%" alt="Privileged Identity Management"/>
  
<p/>

- IT admins have the ability to assigna a user with time-bound access

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167491857-528b6f43-12fd-47e3-9b27-72369092fac9.png" height="55%" width="55%" alt="Privileged Identity Management"/>
  
<p/>


- User must activate role assigned by IT admin. MFA may be required.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167493223-2bc44b24-0511-46d6-8dd1-c8b2859d67e9.png" height="285%" width="285%" alt="Privileged Identity Management"/>
  
<p/>

- After a user activates a role, MFA will be required. It acts a another layer of protection for privileged roles.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167493820-3347c16e-cfce-4e0e-8c6f-4a100016788a.png" height="60%" width="60%" alt="Privileged Identity Management"/>
  
<p/>


# Privileged Identity Management -  RBAC Roles for Azure Resources
- Not only does PIM offer management for Azure AD Roles, PIM also manages RBAC roles.





How to manage RBAC roles
- Navigate to PIM > Azure Resources > Select your resource within the subscription > Select Assignments and add the assignment
- <em> Remember, before adding assignments for RBAC roles, IT admins may need to "Discover Resources" so that PIM can identify the resources within the Azure Subscription.
  
Navigate to PIM > Azure Resources
 - Note that IT admins may need to select "Discover Resources" so that PIM can identigy the resources within your subscription

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167534936-ddfc44f1-e83a-4a42-aea3-3bc574496f52.png" height="200%" width="200%" alt="Privileged Identity Management"/>
  
<p/>

- Select Assignments and add a new assignment 
  
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167535117-f858359a-29cd-4630-91d9-e6dd77419912.png" height="120%" width="120%" alt="Privileged Identity Management"/>
  
<p/>

- Notice that these are RBAC roles and not Azure AD roles 
  
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167535342-6983437a-a670-422a-b8b7-94cf50bd9be0.png" height="60%" width="60%" alt="Privileged Identity Management"/>
  
<p/>

- Also notice that time-bound restrictions can be applied to the RBAC roles
  
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167535317-f33ad89c-83e3-4110-a986-05b7a7942e02.png" height="60%" width="60%" alt="Privileged Identity Management"/>
  
<p/>
  
  
# PIM Access Reviews - Azure AD Roles and RBAC Roles
- PIM also offers IT admins to create User Access Reviews for particular roles.
  
  
  
How to create access reviews?
  
- Navigate to Azure AD or Azure Resources 
  
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167537311-2cebd706-8cb2-4116-8ac3-b3fc670d52df.png" height="20%" width="20%" alt="Privileged Identity Management"/>
  
<p/>
  

- If user selects Azure AD blade, select Access Reviews and add an access review
  
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167537695-ebaa9cf8-77e4-470d-8e84-d3678c22fc20.png" height="60%" width="60%" alt="Privileged Identity Management"/>
  
<p/>


  
  
- If user selects Azure Resources, select the resource that needs an access review, then select "Access Review"
- Remember, if the Azure resource does not appear, the user must select Discover or Activate a role.
  
<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/167537806-1b6799bb-0145-481a-a098-c0c6807eadef.png" height="150%" width="150%" alt="Privileged Identity Management"/>
  
<p/>
  
  

