# BT-Dongle-Compatibility-List DS4Windows

**Testing List For BT dongles, both built in and external. For use with DS4Windows and other software.**

Most BT dongles are compatible, but also most has some kind of limitation when comes to multiple controllers at the same time.


| Dongle Model  | BT Version | One Controller  | Two Controllers | Three Controllers  | Four Controllers | BT headset  | Comment | Comment  | Comment |
| ------------- | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: |
| Intel AX200  | 5  | ✓  | x  | x  | x  | BT Headset Wont connect  | When using DS, fine for DS4  | Empty  | Empty  |
| Intel AX201  | 5  | ✓  | x  | x  | x  | BT Headset Wont connect  | When using DS, fine for DS4  | 2 controllers sometimes work for some time  | Empty  |
| Intel AX210  | 5  | ✓  | x  | x  | x  | BT Headset Wont connect  | When using DS, fine for DS4  | Empty  | Empty  |
| Intel AX211  | 5  | ✓  | x  | x  | x  | BT Headset Wont connect  | When using DS, fine for DS4  | Empty  | Empty  |
| Intel AX411  | 5  | ✓  | x  | x  | x  | BT Headset Wont connect  | When using DS, fine for DS4  | Empty  | Empty  |
| Intel Killer AX1650  | 5  | ✓  | x  | x  | x  | BT Headset Wont connect  | When using DS, fine for DS4  | Empty  | Empty  |
| Intel BE200  | 5.4  | ✓  | Not tested  | Not Tested  | Not tested  | Not Tested  | x  | Empty  | Empty  |
| Intel BE201  | 5.4  | ✓  | Not tested  | Not Tested  | Not tested  | Not Tested  | x  | Empty  | Empty  |
| Intel BE202  | 5.4  | ✓  | Not tested  | Not Tested  | Not tested  | Not Tested  | x  | Empty  | Empty  |
| Test  | 5  | ✓  | x  | x  | x  | x  | x  | Empty  | Empty  |
| Generic V5.0 | 5  | ✓  | x  | x  | x  | x  | x  | VID_0A12 PID_0001  | CSR Chip  |
| Realtek RTL8852AE  | 5.2  | ✓  | ✓  | ✓   | Not tested  | Not tested  |   | Empty| Empty  |
| Realtek RTL8852CE  | 5.3  | ✓  | ✓  | ✓   | Not tested  | Not tested  |   | Empty| Empty  |
| Mediatek MT7922  | 5.2  | ✓  | Not tested  | Not Tested  | Not tested  | Not Tested  | x  | Empty  | Empty  |
| Mediatek MT7925  | 5.3  | ✓  | Not tested  | Not Tested  | Not tested  | Not Tested  | x  | Empty  | Empty  |
| ASUS BT500  | 5  | ✓  | ✓  | Not tested  | Not tested  | x  | x  | Empty  | Realtek Chip  |
| TPLINK UB400  | 4  | ✓  | ✓  | Not tested  | Not tested  | Fine with one DS  | Skip BT Audio with 2 DS  | Empty  | CSR Chip  |
| TPLINK UB500  | 5  | ✓  | ✓  | ✓   | ✓  | Fine with four DS  |   | VID_2357 PID_0604| Realtek Chip  |

| TPLINK UB400 v1.1 | 4  | ✓  | ✓  | Not tested  | Not tested  | Fine with one DS  |   | Empty  | Realtek Chip  |
| TPLINK UB500  | 5  | ✓  | ✓  | ✓   | Not tested  | Fine with four DS  | ✓  | VID_2357 PID_0604| Realtek Chip  |
| TPLINK UB500 PLUS | 5  | ✓  | ✓  | ✓   | Not tested  | Fine with four DS  | ✓  | | Realtek Chip  |





IMPORTANT: A major release was made by intel (feb 2024) that improves connection when using more than one controller. Please install INTEL BT driver 23.80.0 or newer.

** If using 3 or 4 Dualsense controllers consider getting a USB male-female extension wire to plug the Bluetooth dongle into and make sure its facing in the direction of the controllers. If not, extra latency might be felt or the controllers might just not register inputs at all. Also, connect the controllers first before BT headset/speaker.

*DS = Dualsense

*DS4 = DualShock 4

*BT Headset = Any brand BT headset

DATA is reported by users. There is no guarantee it will work the same for you. Use at your own risk.
