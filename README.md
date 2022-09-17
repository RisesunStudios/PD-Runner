<h1 align="center">
  <br>
  <a href="https://bit.ly/3Ptat3Q">
  <img src="https://bit.ly/3PB8V85" width="180" height="auto"
  alt="PD Runner">
  </a><br>
  PD Runner 0.3.8
  <br>
</h1>
 
<p align="center">Tool for Parallels Desktop that start
<br>VMs even after the trial is expired</p>

## 🛠 Usage Guide
[![Buy Me A Coffee](https://img.shields.io/open-vsx/stars/redhat/java?color=D8B024&label=buy%20me%20a%20coffee&style=plastic)](https://www.buymeacoffee.com/utsanjan)‎ ‎
[![](https://img.shields.io/github/license/DopeSatan/PD-Runner?logoColor=red&style=plastic)](https://github.com/utsanjan/Tsunami-Bomber-Android/blob/main/LICENSE)‎ ‎ <br>
- Download [Parallels Desktop](https://www.parallels.com/)
- Activate the trial period inside it
- Download the **"PD Runner.zip"** file below
- Extract the zip file and get the **"PD Runner.app"**
- Copy **"PD Runner.app"** to the **"Applications"** Folder
- Run the following command in the terminal with admin rights
```
sudo chmod +x /Applications/PD\ Runner.app/patch && sudo sh /Applications/PD\ Runner.app/patch
```
- Click the menubar icon to list all the VMs on your Mac
- Start any VM with `PD Runner` by clicking on it from the list<br>

<a href="https://github.com/utsanjan/PD-Runner/blob/main/Releases.md">
<img src="https://bit.ly/3Ee49cs" alt="Tsunami App Download" width="200"></a><br>ㅤ

> ## DISCLAIMER:
> **Only for learning and research use!<br>
> Please delete this within twenty four<br>
> hours after downloading PD Runner.**

## ❓ Frequently Asked Questions
**1. Why do I need to enter a password when first run?**  
> Because of the new authentication measure introduced in PD 17.1.0, you need to bypass it by quickly switching the system time. A "Privileged Helper" needs to be installed on the system to change the time.  
> If you don't do this, you will need to enter the password every time you start an VM.  

**2. Why does PD Runner start without any windows?**  
>PD Runner is a menu-based application, it only show an icon in the menu bar for use after starting, and there is no main window.  

**3.  Why do I get an warning while running or installing PD Runner?**  

<img width="300" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjnlV0m-2so4STjDi4U1OzyvKfOCcBaLVALyEFrA7x0eQOpf3e65vVObqTCROX7HppyNTOJBufUj34VasxPw6QEbPkdo_XklYiLIlY6XHJcyCFhZi9umw4DKV3OVKousZphozKeKBgLqmTz5-ONfYPy6Kj3bqpO9uEYeBnU_Ld5wEMVW_MTFy7HcpAm/s16000/184446703-2696af41-f626-4dfd-a5a0-b4e54865bd19-modified.png" /> 

> If you get an error message as shown in the picture above please uninstall the PD Runner app from the Applications folder and then run the following command in Terminal as admin. Lastly, install the latest PD Runner app from the releases section of this repository and it will work normally again. 
```
 sudo bash -c 'rm -rf /Library/PrivilegedHelperTools/com.lihaoyun6.PD-Runner-Helper && launchctl enable system/com.lihaoyun6.PD-Runner-Helper'
```

**4. Do I need to change the VM to a specific name to use it?**  
> No, PD Runner can automatically list the VMs in the current system automatically.

**5. Why does it say that PD Runner is damaged?**  

<img width="260" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjkWUI1RmBuPA2lXpEQxj3fJnwmU99JoVxHmyx1BeYExOdGxYDd2ydL0vXlX124u9f2yLshDkvs6oPXyE2WJN1epO9Ycr-drms3YjOq1ZJT-oqPvhUycK3X5Z5zOVWd7OfsvsjT0FxmT3r-ndeP2dckrBovmsyhaz3QbYiMSd1IAzOE-u2Wd82W5b6V/s1600/Untitled%20design-modified.png" /> 

> If you get a message as shown in the picture above then run the following command in Terminal as admin and the application will start to function normally again. 
```
 sudo spctl --master-disable && xattr -cr /Applications/PD\ Runner.app
```

##### ‼️ NOTE: If you still face any issues you can state it [here](https://github.com/utsanjan/PD-Runner/issues/new/choose).

## ✒️ Credits
[lihaoyun6](https://github.com/lihaoyun6/) and [MikeWang000000](https://github.com/MikeWang000000/) originally made the PD Runner app for macOS. But the repository was taken down due to a DMCA takedown notice. Hence, the credits goes to them for creating this amazing application. You can read more about the DMCA takedown notice from [here](https://github.com/github/dmca/blob/master/2022/01/2022-01-19-parallels.md).

## 📞 Contacts
For Queries: [My Instagram Profile](https://www.instagram.com/utsanjan/)  
[Check Out My YouTube Channel](https://www.youtube.com/DopeSatan)
