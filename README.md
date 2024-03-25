### This is the begainer guide to unlock bootloader.If u don't have any knowledge about this don't worry i will explain each step from beginning.




## Requirements
👉 Need a Laptop💻/Pc🖥️ or Any other device👨‍💻(to run commands).
<br>👉 Having a way to restore♻️ stock if any device bricks📲 occurs.
<br>👉 A data cable that supports fastboot mode.(generally original will support).

<br>
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
💢 Now run ```adb reboot bootloader``` 

