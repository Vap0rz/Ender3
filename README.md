# Ender3
Preconfigured files for Ender3, TH3D Firmware and BLTouch (version3)
The offsets are good for the Creality BLTouch addon. I also increasing the speed for autoprobing (roughly 25 seconds now) and it still works as intended. You may have to go back and adjust offsets if you are using binder clips on the bed. 

Directions:
Connect printer via USB cable
Copy files over to your TH3D/firmware directory
Launch the TH3D arduino IDE
Open TH3DUF_R2_blt.ino
Ensure your board is set to Sanguino 128p 
Set com port
Ensure CPU is set to ATmega 1284p (16Mhz)
Set Programmer to Arduino as ISP
Check by compiling and then flashing
Enjoy
