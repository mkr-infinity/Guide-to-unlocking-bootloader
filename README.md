### This is the begainer guide to unlock bootloader by Kaif😇. <br> If u don't have any knowledge about this don't worry i will explain each step from beginning.

[SEE THIS FOR LOCKING🔒 THE BOOTLOADER](#for-locking-bootloader)
## Requirements
👉 Need a Laptop💻/Pc🖥️ or Any other device👨‍💻(to run commands).
<br>👉 Having a way to restore♻️ stock if any device bricks📲 occurs.
<br>👉 A data cable that supports fastboot mode.(generally original will support).

<br>

>[!WARNING]
>❗This process will erase all your user data(like factory reset)
<br>❗So remember to do full backup if your data is important.


<br>

>[!NOTE]
>I hope u have read all instructions before starting😇.

<br>

# Starting
#### Enabling Developer Option.
🔑On your device settings search for ```build number``` and click on it seven times. <br> 🔑Unlock your device <br> 🔑Now Developer option has been enabled.

#### Enabling USB Debugging and OEM unlocking mode.
🔆Open developer option you will find an option USB Debugging Mode just enable it.
![USB debugging ON.jpg](https://github.com/mkr-infinity/Guide-to-unlocking-bootloader/assets/125804924/f0b86755-1772-49a1-bfcc-8090f349f4a6)

🔆Also enable OEM Unlocking option.

![OEM unlocked option.jpg](https://github.com/mkr-infinity/Guide-to-unlocking-bootloader/assets/125804924/542d3ee5-6a35-4c9f-a5c3-a70d09f2471c)

####  Connecting device to pc,laptop,from where you want to run commands.
🔗 connect usb to device and plug to pc. <br>
🖥️Open CMD or Powershell(WIN+R type ```cmd``` press Enter) <br>
📜Now run ```adb devices``` to see if your device is connected or not.
![adb devics.png](https://github.com/mkr-infinity/Guide-to-unlocking-bootloader/assets/125804924/8d62d8ac-5744-4f2d-8161-a94b8087f5d0)

☝️☝️☝️ if showing a device like this then everything 🆗<br>

>[!NOTE]
>🔀If your device is not showing then try to connect data cable/usb correctly or try another data cable.
><br>🔀If data cable is original then check if u have missed enabling usb debugging.

👉proceeding to next step after correctly showing attached devices.

#### Running Commands.
💢Now run ```adb reboot bootloader``` (it will reboot your device to fastboot mode) <br>
💢Now you are in ⏩ fastboot mode.😇 <br>
💢To check if device is connected or not run👉 ```fastboot devices``` , if it shows a device,then connected correctly. <br>
💢Run ```fastboot flashing unlock``` <br>

after this ☝️ you will receive a prompt to unlock the bootloader in device😇. <br>
⚠️Just use volume down and volume up button and select yes , then press power button on device. <br>
#### You may stuck at waiting for devices👇
![ADB reboot bootloader waiting problem.png](https://github.com/mkr-infinity/Guide-to-unlocking-bootloader/assets/125804924/52fda683-e389-4ce6-85a7-a8a15d8f75a8)

>[!TIP]
>🤦‍♂️ I HAVE ALREADY TOLD U TO USE WORKING DATA CABLE. <br>
>👉 U CAN TRY WITH REINSERTING DATA CABLE. <br>
>👉 JUST REMOVE AND INSERT DATA CABLE AGAIN.

After reconnecting run 👉 ```fastboot flashing unlock``` again to show the bootloader prompt.<br>
Then [follow same.](#running-commands)
<br>
#### Unlocking the bootloader successfully.
🙅‍♂️Afyer successfully unlocking u will see like this in pc👇
![fastboot flahsing unlock.png](https://github.com/mkr-infinity/Guide-to-unlocking-bootloader/assets/125804924/a2309998-2627-41d0-ae72-88e377943919)
<br>
🤷‍♂️Now run ```fastboot reboot``` ( device will reboot now )
<br>
⚠️While rebooting you will see a message like this👇
![Unlocked successfully.jpg](https://github.com/mkr-infinity/Guide-to-unlocking-bootloader/assets/125804924/315e3320-e205-4d28-9e4b-d59013b5b9e1)
<br>
😇🙅‍♂️ These are the proofs that we have unlocked our bootloader successfully.
<br>


## For Locking Bootloader
🇮🇳 I think you are irritated while unlocked bootloader 😂🤣 <br>
🇮🇳 so for u Another way to lock the bootloader🛅
🇮🇳 All steps are same only run ```fastboot flashing lock``` instead of running ```fastboot flashing unlock```  and follow same method.



#### If u found something wrong in this connect with me.
<div id="badges">
  <a href="https://www.instagram.com/mkr_infinity/">
    <img src="https://img.shields.io/badge/Instagram-red?style=for-the-badge&logo=Instagram&logoColor=blue" alt="Instagram Badge"/>
  </a>  
</div>

<div id="badges">
  <a href="https://t.me/mkr_infinity">
    <img src="https://img.shields.io/badge/Telegram-red?style=for-the-badge&logo=telegram&logoColor=blue" alt="Instagram Badge"/>
  </a>  
</div>
