# Virtual Machine 💃

### ❣ [MacOS, Linux ]  [ CPU 3core - 7GB Ram - 256 SSD ]


<br>

## Setting up:
1. Fork this project
2. Go to your peoject page, click `Settings` and go to `Secrets`, and then click `New Secret` to add these secrets below:

Link How To Install Windows: https://github.com/4irjej/Windows-In-MacOS-Runners


Secrets Name | Uses | Notes
----- | ----- | -----
`NGROK_AUTH_TOKEN` | For **ngrok** tunnel uses | Go to website, and copy the API key from https://dashboard.ngrok.com/auth/your-authtoken
`MAC_REALNAME` | For MacOS User Display Name | Type any name you want
`MAC_USER_PASSWORD` | For MacOS System Admin Password | Type any password you want
`VNC_PASSWORD` | For the login password of VNC remote authentication | Type any password you want
`LINUX_USERNAME` | For linux system username | Type any name you want
`LINUX_USER_PASSWORD` | For linux shell and root password | Type any password you want
`LINUX_MACHINE_NAME` | For Linux System Computer name | Type any name you want
`CHROME_HEADLESS_CODE` | For remoting linux desktop using google remote | Copy Codes from [here](https://remotedesktop.google.com/headless) and login with your google account, and then copy the code below `Debian Linux` blank. :warning: Each code can only be used for once, generate another code when u have used that one.

## Deploy and Run
<details>
    <summary>MacOS Install and Run</summary>
<br>
    
1. go to `Actions` Tab and select one of system workflow.

2. Click `Run Workflow` button on the left of `This workflow has a workflow_dispatch event trigger` line.

3. Wait until a few minutes.

4. Go to https://dashboard.ngrok.com/status/tunnels and check if theres a one online tunnel running.

5. Copy the link(**without tcp://**) and go to VNC Viewer(Download and install it), input the link to connect area u copied from the website.

6. Fill in those login info, within username `Avishkar`and password from `VNC_PASSWORD` you typed.

7. Enjoy!

</details>

<details>
    <summary>Linux</summary>
<br>

1. First, start the actions of Linux System.
2. Second, Copy the link from the console
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/0F804C5F-FE8F-45FA-9720-F91F212597DF.png" >
3. Go to MacOS Terminal or Windows CMD Terminal or else ssh client and enter command provided. Enter your ssh password then.
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/78FE6C5A-7270-4986-AB8F-57EC4C9B4F44.png" >
4. ENJOY!

</details>

---

### Screenshots:

<details>
    <summary>Ubuntu (SSH Version)</summary>
<br>

1. Click **Run Workflox**
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/96644176-D760-47D4-BED2-C47E62A6763F.png" >

2. Copy ssh with url
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/0F804C5F-FE8F-45FA-9720-F91F212597DF.png" >

3. Open cmd or Terminal from your windows/MacOS or Linux, and type command provided by github actions boxes.
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/78FE6C5A-7270-4986-AB8F-57EC4C9B4F44.png" >

type **yes** from the connect, and then type your ssh password by secrets of LINUX_USER_PASSWORD u have set.

4. Type **sudo -i** for root permission and type your password.
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/E5527744-1ED1-4550-8867-EF4EC76D6895.png" >

5. Enjoy having your FREE linux SSH VPS and type any command you want.(but only 6 hours)
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/E6E9EA63-AC24-4FDB-AAF9-8B509658440A.png" >

</details>

<details>
    <summary>Ubuntu (Desktop Remote Version)</summary>
<br>

- Desktop Screenshot
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/4EB9C2FF-9D03-4998-A440-D7716A0F7CD0.png" >

- Linux Chrome
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/09F0A4CF-9B30-44CD-8DC4-139D03DFC2CC.png" >

- Install any apps you want :)
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/A0886141-DF1E-4379-88E7-F00EDAD87D0E.png">

</details>

<details>
    <summary>MacOS</summary>
<br>

- Desktop Screenshot
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.32.41%20AM.png" >

- Settings
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.32.21%20AM.png" >

- RAM
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.32.58%20AM.png" >

- Storage
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.33.18%20AM.png" >

- Pre-Installed Apps
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.34.10%20AM.png" >

</details>


<details>
    <summary>⚠ Warnings </summary>
<br>
    
```py
THIS IS ONLY FOR EDUCATIONAL PURPOSES

DON'T USE FOR MINING OR ILLEGAL USE

DON'T RECODE THIS SC!
```
    
- Reminders:

:warning: Dont install big sur updates on your macos virtual machine, it will break your remote process!
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.35.57%20AM.png">
</details>

---
