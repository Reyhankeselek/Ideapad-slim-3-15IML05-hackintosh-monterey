# Lenovo-ideapad-slim-3-15IML05-hackintosh-Monterey
Functional, ready to use, perfect efi for lenovo ideapad slim 3 15IML05 HACKINTOSH

But remember to enter your smbios first before using it!

Please to make sure that you have the same model and bios version, but remember : **IDEAPAD AND IDEAPAD-SLIM IS NOT THE SAME**

Model            : LENOVO-IDEAPAD-SLIM-3 15IML05 

Bios             : DXCN44WW 

Cpu              : i3-10110u cometlake-u

Ram              : 4gb micron

Storage          :NVMe SSSTC_CL1-4D256_SSD 256 gb

Wifi adapter     : intel wireless ac 9560

Audio            : realtek audio 230

If you have lenovo laptop close enough to this model please do not use this efi as is, you have to configure it yourself with dortania open core guide according to your cpu model


# https://dortania.github.io/OpenCore-Install-Guide/


# Working :
Wifi(HeliPort),
Sleep,
Keyboard,
Screen brightness,
Audio,
Usb port (all),
Camera,
Bluetooth,
Battery status,
Headphone jack,
Display brightness hotkey,
Mousepad / trackpad,
PowerButton (CTRL + POWER).

# Not working :
iservices

# Not tested :
Hdmi port,
Sd card reader.


# How to use :

Put your smbios in the config.plist

Generate ssdt's with ssdttime : ssdt-EC,ssdt-HPET,ssdt-PNLF.ssdt-RTCAWAC,ssdt-XOSI

Put the generated ssdt's in the EFI>OC>ACPI folder

Install mac os Monterey

And after installing mac os : install HeliPort

# Troubleshooting :

1 If it does not boot or it goes to black screen and restarted you can try :

enabling/disabling dsdt (dsdt is disabled by default)

recreate mac os installer


2 If ghostbuster logo appear you can try :

enable verbose mode and googling the error message

try different smbios


3 If kernel panic appears after installing mac os you can try:

setting the date to 2019 and reinstall mac os

configure your bios settings


**And please use this at your own risk!!!**
![Screen Shot 2023-07-25 at 5 19 54 PM](https://github.com/Reyhankeselek/Ideapad-slim-3-15IML05-hackintosh-monterey/assets/87765920/a2e62f49-8715-4570-a391-e7f8ea1b60cf)
![Screen Shot 2023-07-25 at 5 18 58 PM](https://github.com/Reyhankeselek/Ideapad-slim-3-15IML05-hackintosh-monterey/assets/87765920/364f00c3-f5b7-4e20-b3e1-9120364426ff)
