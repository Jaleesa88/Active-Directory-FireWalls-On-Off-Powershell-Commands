### Hello My Name is Jaleesa Perry-Mack


<h1>INFORMATION TECHNOLOGY PROJECT</h1>
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/a00506c3-3d1e-4e0f-b6fa-5364e3e513b1" />

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

<br />Select Mydomain.com <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/e90eb5ad-d9fd-41ff-b145-b756da208284" />


<br />Select New<br />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/97e0d042-42f4-4f0a-8ed9-13f16df1eb0a" />


<br />Click Organization Unit <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/bb518238-cf21-42f6-8b2f-c0fedb9831c9" />


<br />Type in Name box _Employee & Select ok <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/160e1551-cc2e-4c64-b007-3a6c8a8da225" />

<h2>Turning Firewall Off</h2>


<br />Open Server Manager & Click Windows Defender Firewall Properties <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/7f83d705-37a3-4115-ada4-7af05afdb9ae" />


<br />Turn Domain Profile Fire Wall State Off <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/f8186dc0-cba9-4c7f-acc7-ac34af4f9e0e" />


<br />Turn Private Profile Fire Wall State Off <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/0c09b3d7-eeb6-4ef9-8a33-37f545bad20a" />


<br />Turn Public Profile Fire Wall State Off <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/bcb23d84-10fb-4021-b3a3-fd958b0908e5" />


<br />Display Over View that all 3 Firewalls has been turn off <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/f09755f2-9fe6-40fd-8226-b584a5aea51b" />



<h2>Powershell Commands</h2>

<br />1. Use Command Ping on IP Address 10.0.0.4 to insure IP Address is Working 
2. Use Command Host Name to show name of a computer and network name: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/24a4e05a-f8ac-49f3-a401-412700cc4ecd" />


<br />Use Command ipconfig/all to show detailed network information about a Computer: <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/ac85664e-2104-4541-856d-6de4bcda6634" />








<h1> MICROSOFT AZURE PROJECTS </h1>
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/b4a25e55-08fe-4fad-8dc9-cfa56ba52856" />


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


<d />Select Resource Group <d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/42c00884-37ce-423e-95d7-b6da24139c43" />


<d />Select Create <d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/3e38a90f-98bc-4204-9efd-fc417b023482" />

<d />Confirm Resource Group was Created<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/e872e5cc-1c67-4e08-953d-321558669342" />


<h2>CREATING VIRTUAL MACHINES</h2>

<d />Select Virtual Machine<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/1f4604d3-8027-457f-829e-04601bdad940" />


<d />Select Resource Group you previous Created<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/4638ece4-89ac-464f-99df-0cc49154e914" />


<d />Type in VM-1 in Virtual Machine name box<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/7cb04ada-0117-40ac-a40d-25736b4b4d17" />


<d />1.Fill out User Name, Password, and Confirm Password. 2. Select Check box on bottome of page next to I confirm<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/1a90a14c-4b88-46d0-a750-a17c68c7d55f" />


<d />Change Image Configure VM<d /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/3ddbc68d-df5c-4369-a151-da18b3b338fd" />


<d />Select check box under licensing<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/20b89260-3df8-4b1f-962a-df8f853671a0" />


<d />Click Review & Create<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/6cfae8ab-e0c8-4597-bdd9-64c89728b885" />


<d />Once Validation passed appears in green highlighted message, Click Create<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/76244b37-b59e-4f10-9184-8282b07a7739" />


<d />Wait for Deployment to Succeed to ensure you did everything correct<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/3e6fb6a6-dcdf-4ac5-aab1-9dff06dc5cc4" />





<h2>CHANGING STATIC IN DOMAIN CONTROLLER</h2>

<d />Select DC-1<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/46e1bfff-6327-4851-be90-86ae844a2341" />


<d />Left side of New Screen Select Networking Setting<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/4e4ace1c-129e-4c22-a981-25762bc557a8" />


<d />Select on Network Interface IP Configuration<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/65ce916c-b366-4a70-b073-7377e22bcce2" />


<d />Select on Ipconfig <d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/0b22e3f6-d76d-4c7a-a666-b9ee0ca6b66c" />

<d />1. Change Allocation to Static 2. Enter IP Address 3.Select Save<d />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/73e4e527-e7ee-4d5a-9f16-eb584bfa0107" />










<h1>Remote Desktop Project</h1>

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/6ff6bdb0-e206-467d-8ed1-0dace1a7a712" />

<h2>Enviroments and Technologies Used</h2>

- Microsoft Azure Resouce Group

- Micrososft Azure Virtual Machine

- Remote Desktop


<h2>Operating Systems Used</h2>

- Windows 11 Pro (version 24HZ)

- Domain Controller

- Windows Server 2022

<h2>Steps to Create Remote Desktop</h2>


<b /> Select VM-1 <b /> 




<b /> COPY PUBLIC IP ADDRESS <b /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/95ef0474-97da-437f-a367-c99957052327" />





<b /> ADD PC <b />  
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/a6597cc2-ef0f-4856-b23c-2e9a15994b8a" />




<b /> 1.PASTE COPY PUBLIC IP ADDRESS IN PC NAME SECTION 2.IN FRIENDLY NAME SECTION CREATE NAME FOR PC & CLICK OK <b />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/28de70a0-a4b6-49ca-aa93-30b2973127be" />



<b /> CLICK ON 3 DOTS ON TOP RIGHT SIDE OF CREATED PC & CLICK CONNECT <b /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/4e2b1adb-32e1-41fe-83ba-3d8884195547" />



<b /> ENTER CREDENTIALS FOR USER NAME (SAME AS PC NAME) & PASSWORD <b />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/6f726c21-f8d2-4904-bf01-1a3d45bb5b41" />


<b /> REMOTE PC WELCOME PAGE WILL APPEAR <b />  
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/1708e7aa-82ab-4b10-84a5-cf4048bfe9d6" />



<b /> WINDOW HOME SCREEN WILL APPEAR WHEN REMOTE ACCESS IS CONNECTED <b /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/9d2b7c46-4787-4329-8f77-3e2ebf54c65b" />













<h1>OS TICKET PROJECT</h1>

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/dca68094-1170-4145-a2f9-10f0fd15cb2d" />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure VM

- Remote Desktop

<h2>Operating Systems Used</h2>

- Microsoft Azure

- Windows 11

- Os Ticket

  <h2>OS Ticket Steps</h2>

  -Create Ticket as a End User

  -Create New Agent

  -Create New Team 

  -Create Service Level Agreement


<h2>Create Ticket as a End User</h2>

<br />SELECT OPEN A NEW TICKET <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/0d768e6d-72cb-44e0-ac18-d60ee4507cec" />

<br />ENTER CONTACT INFORMATION FOR KAREN & CLICK CREATE TICKET <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/eb1e5f38-1a21-445f-8633-603fc8606eea" />

<br />UNDER HELP TOPIC DROP BOX SELECT REPORT A PROBLEM & UNDER ISSUE SUMMARY GIVE A BRIEF STATEMENT OF OCCURING ISSUE <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/76180ccf-3c13-46e7-bbd4-cff4a5ccdd59" />

<br />CLICK CREATE TICKET <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/807bd0d0-6428-423e-9237-eef114087a9e" />

<br />SUPPORT TICKET REQUEST SUCCESSFULLY CREATED <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/01f30a0b-056f-44a7-bb17-59f6fa41dc1b" />








<h2>CREATE NEW AGENT </h2>

<br />STEP 1: SELECT AGENT TAB <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/b300c47e-2cd6-4adf-95ab-fd9d0734e9d4" />

<br />STEP 2: SELECT ADD NEW AGENT <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/8719ed72-f248-4f20-b2ad-706b7581af8a" />

<br />STEP 3: ADD NEW AGENT KAREN ANDERSON <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/784edb55-58a9-4f84-9845-a3cdc3b43883" />

<br />STEP 4: SET KAREN PASSWORD <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/26ce4b62-3a49-4f4c-90b1-d9239cd9fb44" />

<br />STEP 5: SET KAREN STATUS UNDER ACCOUNT TAB <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/126e6379-4670-4aa6-82f0-fc632277b0c5" />

<br />STEP 6: UNDER ACCESS TAB SET KAREN ACCESS TO LIMITED ACCESS <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/45146f2d-131c-4a75-96b4-dc76635025f3" />

<br />STEP 7: UNDER PERMISSION TAB CHECK ALL UNDER USER TAB & CLICK CREATE <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/de8da598-0abf-4329-af3c-6a8d0bb96c8b" />

<br />STEP 8: UNDER TEAMS TAB ASSIGN KAREN LEVEL 1 SUPPORT & CLICK SAVE CHANGES <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/5e52b8bb-6360-42f9-b32c-46810a5e045f" />

<br />SUCCESSFULLY ADDED KAREN <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/32a463fe-5310-4647-a763-d55d894d3462" />


<h2>CREATE NEW TEAM </h2>

<br />STEP 1: SELECT TEAMS UNDER AGENT TAB <br /> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/63176e37-968d-4e73-bf48-4bae861ee953" />

<br />STEP 2: SELECT ADD NEW TEAMS <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/fae94764-1d14-4c29-ae88-ebb10537c430" />

<br />STEP 3: CREATE NAME FOR TEAM & CLICK CREATE <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/8954dead-d4b0-4e93-9512-92e88d777919" />


  



<h2>CREATE SLA </h2>

<br />STEP 1: SELECT MANAGE TAB <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/a7d93d8f-7d1f-47e6-9533-c910a6518f82" />

<br />STEP 2: SELECT SLA TAB <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/bd5420a9-47f5-49e0-8cff-9bcb962d692e" />

<br />STEP 3: SELECT ADD NEW SLA PLAN <br/>
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/06fd502b-d287-4d05-b7f0-9c8f01577e5d" />

<br />STEP 4: CREATE NAME AS SEV-A, ADD 1 HOUR FOR GRACE PERIOD, SELECT 24/7 SCHEDULE IN DROP BOX, AND CLICK CREATE <br />
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/59e3ae25-0a8d-473d-b7f4-1794d65e0563" />

<br />SLA SUCCESSFULLY ADDED <br/> 
<img width="3200" height="1800" alt="image" src="https://github.com/user-attachments/assets/71245e7d-6190-47b9-bbef-c24a02663088" />
