<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Virtual Private Networks (VPNs) </h1>
In this tutorial, we observe how VPNs can change a machines location. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Create Resources in Azure
- Observe IP Adress of current machine
- Sign up for ProtonVPN and test the VPN connection
- 

<h2>Actions and Observations</h2>

Step 1: Create a Resource Group in Azure
   - Enter 'Resource Groups' in the search bar at the top
   - Click '+Create'
   - Enter your Resource Group  name, and select whichever Region that works for you
   - Click 'Review + Create' -> then click 'Create'
     ![image](https://github.com/user-attachments/assets/3682dd13-3d4c-4131-b243-3193d3506c03)

Step 2: Create a Virtual Machine
   - Enter 'Virtual Machine' in the search bar at the top
   - Click '+Create'
   - Create the VM inside of the Resource Group you just created.
   - The VM should be in the same region as the Resource Group.
   - Name your "VM"
   - Select "Windows 10 Pro" as the Image.
   - Select 'Standard 2 vcpus, 16 GiB memory' as the Size.
   - Create a username "labuser"
   - Create a Password (Your choice)
   - Confirm the License Agreement
   - Click 'Review + Create' -> then click 'Create'

![image](https://github.com/user-attachments/assets/b87861d9-49bf-4df3-bbf6-a2747691dd9a)

![image](https://github.com/user-attachments/assets/a6f3bb29-2010-49d8-91a6-2536041d7ac0)

![image](https://github.com/user-attachments/assets/95f9364c-4ba4-4b11-954a-5547f9651e45)

![image](https://github.com/user-attachments/assets/a37ece6d-b525-4ece-aae9-bb0f90d5c6ed)

![image](https://github.com/user-attachments/assets/b78d21f6-7898-4d33-a981-921a4df52b96)

![image](https://github.com/user-attachments/assets/70330e6f-b703-48ab-97d1-60a7cffc00c1)

![image](https://github.com/user-attachments/assets/c5acb270-fe75-433b-8272-090f086ce5e6)

Step 3: Use Remote Desktop to sign into VM.
- Open "Remote Desktop"
- Enter the Public IP adress of your VM
- Enter Username and Password
  
  ![image](https://github.com/user-attachments/assets/34e60f3e-30b2-4f50-a22b-2462c28612ed)
  
  ![image](https://github.com/user-attachments/assets/da7bbd7b-8637-4e91-add5-d7eb5398faf3)


  Step 4: Observe IP Adresses and change them.
  - Browse to https://whatismyipaddress.com/ from within your own machine and take note of this in a text file
  - Browse to https://whatismyipaddress.com/ from within your VIRTUAL MACHINE and take note of this in a text file
  - Sign into or Create an account for "ProtonVPN" (in the VM)
  - Go to "Downloads" and select "Windows"
    ![image](https://github.com/user-attachments/assets/f034f1d0-89b4-446d-a3cb-8d28ec9a691f)

    ![image](https://github.com/user-attachments/assets/5e45b3e4-3e22-422f-b911-24caa2b880cc)

    ![image](https://github.com/user-attachments/assets/feb4c0e1-b2bf-41ed-bd7b-394800c93056)

    ![image](https://github.com/user-attachments/assets/8fea995d-3ca6-4689-99cf-3bb40d8fb669)


