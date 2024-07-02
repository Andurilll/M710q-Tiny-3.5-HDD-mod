# M710q-Tiny-3.5-HDD-mod
Adding a 3.5" HDD with 12V to a Lenovo M710q Tiny 
![02-07-2024_09-40-04](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/1a89e9e9-1ee2-4fc3-8e8d-76abf8809ebd)

Goal of this project is to add a 3.5" Harddisk and use internal Sata & 12V.

![20240701_172143](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/5a92d705-190f-4733-bf03-46e5e82cfaf2)


# TL;DR
Solder the yellow wire of a Sata-Extender to 12V on Mainboard

Place HDD outside

# Disclaimer
**USE AT YOUR OWN RISK!!!**

I did not check any max power rating of the soldered point.

I'm not responsible for Board damage or a fire!

# Required Material

* M710q Tiny
* 3.5" Harddisk
* Solder Iron
* SATA extension (power & data) | Aliexpress
* Yellow wire >= 0.75mm<sup>2</sup> L= ~5cm
* Shrink tubing or isolation tape
* Small & medium zip ties
* Multimeter for 20V DC
* Cutter/Knife
* Sidecutter pliers

# How to

1 Open Case

2 Verify the 12V Solderpoint with Multimeter
![20240701_151446](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/04cd8f7b-9c05-4014-98b6-c48ac489e5c2)
![20240701_151335](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/cf9aaff1-57ff-4164-9364-804de6ecbcd7)

3 Cut connector male in half, open hole on the back, put both pieces through separately
![20240701_155635](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/43238d6e-7c6b-4331-93c8-3a3c3f72b4e3)

4 Mount SATA-Female with zip ties

5 Cut yellow wire & solder the short extra wire to it. Isolate connection and cutoff point on male side

6 Solder Wire to 12V Mainboard point
![20240701_160932](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/1744ce7d-3678-424b-82e6-328d2647a4e9)

7 Fix Yellow wire with zip ties to CPU Cooler

8 Fix all wires to SSD-Bracket
![20240701_172044](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/55d69c6f-610f-44ff-a3d7-0f7a83e07e10)

8 Close

# Extra photo for GND/5V/12V
Thanks to systemerror-codenotfound https://cults3d.com/es/modelo-3d/artilugios/3d-printed-nas-case-for-tiny-m710q-m910q-m720q-m920q
![image](https://github.com/Andurilll/M710q-Tiny-3.5-HDD-mod/assets/116340711/4ec6e9d4-585e-4514-8299-0189709304d9)


# To Do's

- [ ] Print 3D bracket for HDD

# Credits

Thanks badger707 for your work with the m920q. https://github.com/badger707/m920q-dual-NVME

The M710q schematics are here available: https://github.com/badger707/m920q-dual-NVME/issues/2  ( https://github.com/badger707/m920q-dual-NVME/files/11174851/ThinkCentre_M710q_LiteON_JC133_IQ270IH1_REVX03_www_DeviceDB_xyz_.pdf )
