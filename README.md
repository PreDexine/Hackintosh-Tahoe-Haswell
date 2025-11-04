# Hackintosh-Tahoe-Haswell
OpenCore EFI configuration to boot MacOS Tahoe on Intel Haswell system.  
Currently using OpenCore 1.0.5 (will be updated when new version released).

# My current specifications:
| **Components** | **Name** | **Notes** |
| -------------- | -------- | --------- |
| **CPU** | Intel Core i7 4790 | 
| **Motherboard** | Asrock H97M Pro4 |
| **GPU** | MSI Radeon RX 5700XT MECH OC | `Kernel panic when using whatevergreen.kext` |
| **RAM** | Kingston 2x8GB DDR3 |
| **Storage** | SK Hynix NVME 512GB |
| **Ethernet** | Intel Gigabit I218-V |
| **Audio** | Realtek ALC892 | `Currently not supported on MacOS 26` |
| **OS** | MacOS 26 | `MacOS 26.1 (25B78)` |

> [!IMPORTANT]
> Some config and kext might need a litte bit modifications depending on your specifications.

# What's working and not working  

- Onboard LAN.
- GPU Metal 3 support.
- Onboard audio not working (AppleHDA was removed from Tahoe, use external audio like DAC or HDMI/DP audio).
- WhateverGreen was removed due to causing kernel panic.
- iService not fully tested (I can login and use my apple account without issue).
- iGPU not tested since I use external GPU (it should work if you configure the PciRoot section properly).
- Changed the GUI on boot section to make it looks like on every mac.

> [!NOTE]
> Depending on your config or specs later might change the functionality.

# Screenshot
![MacOS 26 screenshot](https://idexine.s-ul.eu/175KQZct.jpg)
