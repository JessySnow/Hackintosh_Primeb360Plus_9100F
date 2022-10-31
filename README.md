# OpenCore EFI
OpenCore EFI for Intel 9th Core and Ausu Prime B360 Plus, with build in USB mapper.

## OpenCore version
[OpenCore_0.85_Debug](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.5)

## Hardware
| Hardware | model |
| ---- | ---- |
| CPU | i3-9100F |
| GPU | AMD-5700XT |
| Southbridge Chip | B360-A308 |
| Mouse | HID/I2C |
| Keyboard | HID/I2C |
| Audio encoder | Realtek ALC887 @ Intel Cannon Point PCH - cAVS (Audio, Voice, Speech) [B0]	PCI |
| NIC | Realtek PCIe GbE Family Controller |

## Hint
SMBIOS info should be regenerated, and type into config.plist by your self.

## Tools used
- USBToolBox
- ProperTree
- GenSMBIOS

## Issues

- AppleALC won't work

## Things can be do better

- Manually compile ACPI files