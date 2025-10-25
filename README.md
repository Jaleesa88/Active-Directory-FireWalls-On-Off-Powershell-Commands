### Hello My Name is Jaleesa Perry-Mack


<h1>INFORMATION TECHNOLOGY PROJECT</h1>

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/df33b2dc-40fd-4961-aaf8-a46535412c4a" />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Resource Groups

- Microsoft Azure Virtual Machines

- Domain Controller VM

- PowerShell

<h2>Operating Systems Used</h2>

- Resource Groups

- Virtual Machines

- Windows Server 2022


<h2>Active Directory Steps</h2>

- Create Organizational Unit
  
  - Turning Firewall off

- Create Ticket as a End User

- Powershell Commands

<h2>Creating Organizational Unit</h2>


<br />Click On Mydomain.com: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/e90eb5ad-d9fd-41ff-b145-b756da208284" />


<br />Select New:<br />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/97e0d042-42f4-4f0a-8ed9-13f16df1eb0a" />


<br />Click Organization Unit: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/bb518238-cf21-42f6-8b2f-c0fedb9831c9" />


<br />Type in Name box _Employee and click ok: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/160e1551-cc2e-4c64-b007-3a6c8a8da225" />

<h2>Turning Firewall Off</h2>

<br />Open Server Manager & Click Windows Defender Firewall Properties: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/7f83d705-37a3-4115-ada4-7af05afdb9ae" />

<br />Turn Domain Profile Fire Wall State Off: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/f8186dc0-cba9-4c7f-acc7-ac34af4f9e0e" />

<br />Turn Private Profile Fire Wall State Off: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/0c09b3d7-eeb6-4ef9-8a33-37f545bad20a" />

<br />Turn Public Profile Fire Wall State Off: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/bcb23d84-10fb-4021-b3a3-fd958b0908e5" />

<br />Display Over View that all 3 Firewalls has been turn off: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/f09755f2-9fe6-40fd-8226-b584a5aea51b" />



<h2>Powershell Commands</h2>

<br />1. Use Command Ping on IP Address 10.0.0.4 to insure IP Address is Working 
2. Use Command Host Name to show name of a computer and network name: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/24a4e05a-f8ac-49f3-a401-412700cc4ecd" />

<br />Use Command ipconfig/all to show detailed network information about a Computer: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/ac85664e-2104-4541-856d-6de4bcda6634" />








<h1> MICROSOFT AZURE PROJECTS STEPS </h1>
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/ccb02146-3ada-493d-8de3-f9b789c0467c" />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Resource Groups

- Microsoft Azure Virtual Machines

- IP configurations

<h2>Operating Systems Used </h2>

- Windows 11 Pro (version 24HZ)

- Domain Controller

- Windows Server 2022
 
    
<h2>Steps to Create Deployment</h2> 

- Create Resource Group Steps

- Create Virtual Machine Steps

- Deleting Resource Groups Steps

- Changing Static in Domain Controller

  <h2>CREATING RESOURCE GROUPS</h2>


<d />Click Resource Group <d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/46bed23a-e9f5-4fa8-aaf4-47cbaf82f8d3" />

<d />Click Create <d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/1fbcc261-36b7-458f-a776-a4f6fdeaaf13" />

<d />Confirm Resource Group was Created<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/c23b3350-6745-48f4-931d-5a54890a38c4" />


<h2>CREATING VIRTUAL MACHINES</h2>

<d />Click Virtual Machine<d />
<img width="1600" height="900" alt="Screenshot 2025-08-09 at 6 03 01 PM" src="https://github.com/user-attachments/assets/be85c4d6-b4ca-46f1-a17a-957f3e0a2dd7" />


<d />Select Resource Group you previous Created<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/4c9870da-f729-40f3-912f-2fcd879a5301" />

<d />Type in VM-1 in Virtual Machine name box<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/8021bdac-9116-4ae8-b1f6-7a3214644765" />

<d />1. Fill out User Name, Password, and Confirm Password. 2. Select Check box on bottome of page next to I confirm<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/2b11ed07-1ba2-444d-a519-158e9b2d8322" />

<d />Click Review & Create<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/71ce2c1b-16d5-4710-a35f-f740b0ea101f" />

<d />Once Validation passed appears in green highlighted message, Click Create<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/a55af219-2b9b-4864-8722-77db23b5ddf3" />

<d />Wait for Deployment to Succeed to ensure you did everything correct<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/9e4c65fb-4ae7-42e4-8fb4-0eab0a0df7be" />



<h2>CHANGING STATIC IN DOMAIN CONTROLLER</h2>

<d />Click DC-1<d />
<img width="1600" height="900" alt="Screenshot 2025-08-09 at 6 05 23 PM" src="https://github.com/user-attachments/assets/6f3bee51-dfff-4e83-b8fc-dfcd5b793941" />

<d />Left side of New Screen Click Networking 
<img width="1600" height="900" alt="Screenshot 2025-08-09 at 6 05 40 PM" src="https://github.com/user-attachments/assets/76106699-b1ea-4434-a58e-c315b3de9c08" />

<d />Click on Network Interface IP Configuration<d />
<img width="1600" height="900" alt="Screenshot 2025-08-09 at 6 05 53 PM" src="https://github.com/user-attachments/assets/9cd05a59-28d8-43ad-b932-faa433ffd461" />

<d />Click on Ipconfig <d />
<img width="1600" height="900" alt="Screenshot 2025-08-09 at 6 06 03 PM" src="https://github.com/user-attachments/assets/d199e5d1-9581-4a5d-829e-30338d8bfc65" />

<d />1. Change Allocation to Static 2. Enter IP Address 3.Click Save
<img width="1600" height="900" alt="Screenshot 2025-08-09 at 6 06 15 PM" src="https://github.com/user-attachments/assets/5b9ea4a4-be4d-408f-a931-a883418a684d" /> 








