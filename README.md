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








<h1> MICROSOFT AZURE PROJECTS </h1>
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










<h1>Remote Desktop Project</h1>

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/9c3a6577-93e1-4c42-87fa-6a2483b31707" />

<h2>Enviroments and Technologies Used</h2>

- Microsoft Azure Resouce Group

- Micrososft Azure Virtual Machine

- Remote Desktop


<h2>Operating Systems Used</h2>

- Windows 11 Pro (version 24HZ)

- Domain Controller

- Windows Server 2022

<h2>Steps to Create Remote Desktop</h2>


<b /> CLICK VM-1 <b /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/145dc211-afe7-4e89-9efe-26d5c3c9952f" />



<b /> COPY PUBLIC IP ADDRESS <b /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/cd797538-b799-4558-af3e-56aef3f8d76c" />



<b /> ADD PC <b />  
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/8951844f-d05c-4bab-a53f-ee6b9312745d" />



<b /> 1.PASTE COPY PUBLIC IP ADDRESS IN PC NAME SECTION 2.IN FRIENDLY NAME SECTION CREATE NAME FOR PC & CLICK OK <b />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/60ec7a6f-81fb-4a7f-b6b5-9807fc27cfcf" />



<b /> CLICK ON 3 DOTS ON TOP RIGHT SIDE OF CREATED PC & CLICK CONNECT <b /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/8367083f-9619-41a2-852f-be2953cdfed3" />



<b /> ENTER CREDENTIALS FOR USER NAME (SAME AS PC NAME) & PASSWORD <b />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/6a235056-9d66-46e6-9f49-989dccfb02da" />



<b /> REMOTE PC WELCOME PAGE WILL APPEAR <b />  
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/282bccbd-c4aa-49d6-b969-1f76cd238cdd" />

<b /> WINDOW HOME SCREEN WILL APPEAR WHEN REMOTE ACCESS IS CONNECTED <b /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/e24e3782-cc94-4f33-96f4-443e4fcd8c21" />











<h1>OS TICKET PROJECT</h1>

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/dac5c9b1-2d72-44ea-b597-d5adbbbec6e5" />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure VM

- Remote Desktop

<h2>Operating Systems Used</h2>

- Microsoft Azure

- Windows 11

- Os Ticket

  <h2>OS Ticket Steps</h2>

  -Create Ticket as a End User

  -Create Teams

  -Create Employees

  -Create Service Level Agreement


<h2>Create Ticket as a End User</h2>

<br />Click Open a New Ticket: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/0d768e6d-72cb-44e0-ac18-d60ee4507cec" />

<br />Click on Create a New Ticket <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/eb1e5f38-1a21-445f-8633-603fc8606eea" />

<br />Fill out Contact Information & Select Help Topic: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/76180ccf-3c13-46e7-bbd4-cff4a5ccdd59" />

<br />Fill out issue Summary & Give a brief Summary of Occuring issue: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/807bd0d0-6428-423e-9237-eef114087a9e" />

<br />Click Create Ticket: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/01f30a0b-056f-44a7-bb17-59f6fa41dc1b" />








<h2>Creating Teams</h2>


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/ca101daf-1171-4eae-ac44-4bd5e4d4d880" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/ea50b18b-2dcc-4903-acfa-6b5500762034" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/668c5d7d-7816-4e04-8f02-326381b67e4c" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/be281e73-0854-487c-8ea7-fe30fc42d2cf" />









  <h2>Creating Employees</h2>

  <img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/aed34961-c8a9-433d-af40-fbd1f56b5699" />


  <img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/09a9e2df-62fb-4f9a-a93d-733769aa7938" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/af0540cd-ca72-42c2-98af-a1496eaeb0be" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/d351dc5f-172b-4de3-a3b8-48ca66883397" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/1e80997e-fdfd-4f30-85e2-7eda2aabf37f" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/3617c2cc-91c3-473e-970c-e756a8824936" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/e6f62863-42a4-4b86-9078-40c288df41d0" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/4c44ff45-941b-4123-8579-90935655d41e" />



  



<h2>Creating SLA STEPS</h2>

<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/c6ffca74-f919-4d0f-9617-9048a2f8f413" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/ee5048ad-e0be-4b5a-96ab-3f8ebcbb0334" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/4a36a17a-2f13-4106-8815-d39641a1f6ba" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/3c088b59-d5e8-4b59-9d69-0ae2de617e54" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/b408b6de-bcc6-4d97-a617-ffd1f6fd7cd9" />


<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/23197506-fba8-4cd6-9d68-18dd368ee761" />
