# Hackintosh-Tahoe-Haswell
OpenCore configuration to boot MacOS Tahoe on Intel Haswell cpu.    
**Don't forget to change the SMBIOS to avoid conflict with another devices (use MacPro 7,1 or latest iMac SMBIOS).**

# This configuration was tested on:
**CPU :**    Intel Core i7 4790  
**MOBO :**    Asrock H97M Pro4  
**GPU :**    MSI RX 5700 XT MECH OC  
**RAM :**    16GB DDR3  
**SSD :**    512GB Sk Hynix NVME  

**Some config and kext might need a litte bit modifications depending on your motherboard specifications.* 

# What's working and not working  

- Onboard LAN.
- Full GPU acceleration support (Liquid Glass works perfectly fine).
- Onboard audio not working (maybe due to audio layout but it worked fine on Sequioa).
- iService not fully tested (but I can login and use my apple account without issue).
- iGPU not tested since I use external GPU (it should work if you configure the PciRoot section properly).
- Changed the GUI on boot section to make it looks like on every mac.

**Depending on your config or specs later might change the functionality.*
