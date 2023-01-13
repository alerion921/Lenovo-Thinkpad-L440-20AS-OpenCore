# Lenovo-Thinkpad-L440-20AS-OpenCore-EFI-Monterey-Success

Install EFI (The EFI i used on my USB drive to install OSX Monterey)
Post-Install EFI (The EFI i replaced "install EFI" with after the first boot after completed installation)

English is not my native language so that would be why some of the things i write come of as weird but feel free to ask questions.

Things that does not currently work:
SD Card Reader - Just need to add the relatek kext that RTS5227 PCI Express Card Reader	
PCI Express Card Reader - RTS5227 PCI Express Card Reader	this works for that too but when there is no card in the slot it comes up with an annoying error that the card is of a unknown type so i just disabled SD card and PCI Express Reader cus i dont use them.

There is some issues with sleep i just did not bother to look into them yet because i dont really use it. I prefer to shut down my system :) 

There is also an error where YogaSMC cant detect the CPU fan, i just disabled fan support in YogaSMC panel after reading that there is some issues with the lenovo L systems and the fan reading..

Tried to update SMBIOS and upgrade straight to Ventura from this build 12.6.2 but without any success, i guess it might be because the support for Intel 4600 HD Graphics have been dropped or something else was the error, please tell me if you get this working :)

Other than that i have no issues what so ever..
