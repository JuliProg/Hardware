# Hardware
Hardware for JuliProg

[circuit diagrame](https://github.com/JuliProg/Hardware/wiki/Circuit-diagram)

***
Drivers.rar - A set of drivers for different versions of Windows.

When the "CY7C68013A EZ-USB FX2LP development board" is first connected, the Cypress FX2LP No EEPROM Device USB \ VID_04B4 & PID_8613 appears in the system. You need to install the cyusb3.sys driver (from the Drivers.rar driver package) for your version of Windows in **NORMAL** mode.

After the FIRST start of JuliProg, a new USB device USB \ VID_04B4 & PID_2009 will appear in the system (This is NandFlashInterface). It requires a **FORCED** installation of the cyusb3.sys driver from the Drivers.rar for your version of Windows.

# **REQUIRED** 

In the device properties -> Power Management tab. Uncheck the item
"Allow the computer to turn off this device to save power".

---------------------------------------------------------------------------------------
Added Gerber files for self-manufacturing PCB (NAND_Tsop48 folder).Created by rus89 on https://remont-aud.net/forum

![](https://raw.githubusercontent.com/JuliProg/Wiki/master/img/NAND%20Tsop48_small.jpg) 

Added Gerber files for self-manufacturing PCB (DIP48_Tsop48 folder).Created by rus89 on https://remont-aud.net/forum

![](https://raw.githubusercontent.com/JuliProg/Wiki/master/img/DIP48ToTSOP48_small.jpg)

Added Gerber files for self-manufacturing PCB (BGA63_NAND folder).Created by rus89 on https://remont-aud.net/forum

![](https://raw.githubusercontent.com/JuliProg/Wiki/master/img/BGA63%20NAND%20small.jpg)

