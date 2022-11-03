# Critical error in the circuit , WP # must be connected to PA6

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


# PCB


The archives contain gerber files for self-production of adapters

---

TSOP48 = TSOP48_gerber.zip

![TSOP48 = TSOP48_gerber.zip](https://raw.githubusercontent.com/JuliProg/Wiki/master/img/TSOP48small.jpg)

---

DIP48 to TSOP48 = DIPtoTSOP48.zip

![DIP48 to TSOP48 = DIPtoTSOP48.zip](https://raw.githubusercontent.com/JuliProg/Wiki/master/img/DIPtoTSOP48small.jpg)

---

BGA63 = bga63_gerber.zip

![BGA63](https://raw.githubusercontent.com/JuliProg/Wiki/master/img/BGAsmall.jpg)

