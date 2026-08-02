
Note: This list is still under review, the information in this table maybe be inaccurate to some extent. 

# 📦 List of IDUs

| Model   | Manufacturer                  | Firmware Prefix    | Bootloader Access | DebugPorts | RootAccess | Openwrt_version | Known Issues ?                                          |
| ------- | ----------------------------- | ------------------ | ----------------- | ---------- | ---------- | --------------- | ------------------------------------------------------- |
| IDU6101 | Arcadyan (MTK7621)            | ARCNJIO_JIDU6101_R | ✅                 | uart       | ✅          | 21.02-SNAPSHOT  | 160mhz wont work on fw v2.0.9                           |
| IDU6801 | GMOB                          | GMOBJIO_JIDU6801_R | ✅                 | uart       | ✅          | 21.02-SNAPSHOT  | 160mhz wont work on fw v2.0.9                           |
| IDU6601 | SPED                          | SPEDJIO_JIDU6601_R | ✅                 | uart       | ✅          | 21.02-SNAPSHOT  | 160mhz wont work on fw v2.0.9                           |
| IDU6401 | Sercomm                       | SRCMJIO_JIDU6401_R | ✅                 | uart       | ✅          | 21.02-SNAPSHOT  | 160mhz wont work on fw v2.0.9                           |
| IDU6701 | Skyworth                      | SKYWJIO_JIDU6701_R | ✅                 | uart       | ✅          | 21.02-SNAPSHOT  | 160mhz wont work on fw v2.0.9                           |
| IDU6811 | Telpa                         | JIO_JIDU6J11_R     | ❓                 | uart       | ✅          | 19.07-SNAPSHOT  | Some users faced setting not persisting across reboots. |
| IDU6111 | Arcadyan (IPQ9574/AP-AL02-C1) | JIO_JIDU6J11_R     | ❓                 | uart       | ✅          | 19.07-SNAPSHOT  | LOCKED after fw >R.09                                   |

# 📡 List of ODUs
| Model     | Manufacturer / Assembler      | Module Used       | Firmware_release         | DebugPorts                                         | RootAccess                  | Extra Info                                                                                                                   |
| --------- | ----------------------------- | ----------------- | ------------------------ | -------------------------------------------------- | --------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| JODU51641 | sercomm                     | COMPAL/NXP          | TBD                      | uart❓ usb✅(Onlyusb❓                                         | Not yet, Unconfirmed❓       |                                                                                                                              |
| JODU51642 | sercomm                       | COMPAL/NXP        | TBD                      | uart❓ usb✅(Only fastboot)                          | No❌, fastboot only device   | Fastboot is persistent for an entire boot duration if triggered correctly using hw reset btn. Device is bootloader unlocked. |
| JODU51643 |sercomm                            | COMPAL/NXP                 | ❓                        | uart❓ usb✅(Only❓                                                  | ❓                           |                                                                                                                              |
| JODU51741 | GeneralMobile                 | RG520F-JO(SDX65)  | TBD                      | uart❓ usb✅(exposes only fastboot)                  | No❌, fastboot only device   | Device is bootloader unlocked, flashing is possible.                                                                         |
| JODU52040 | Askey                         | RG500Q-EA (SDX55) | JODU52040_REL_07_27_00_S | uart✅(Password Locked) usb✅(Full adb shell access) | yes✅, via usb -> adb -> ssh | FW is full readonly, kernel lacks overlayfs support, ssh access isn't persistent.                                            |
| JODU52041 | Askey                         | RG500Q-EA(SDX65)  | JODU52041_REL_02_32_00_S | uart✅(Password Locked) usb✅(Full adb shell access) | yes✅, via usb -> adb -> ssh | Same as above. LOCKED on latest fw                                                                                           |
| JODU52121 | LUXSHARE                      |                   | JODU52121_REL_01_15_00_S | uart❓ usb❓                                         | Not yet, Unconfirmed❓       |                                                                                                                              |
| JODU52140 | SPPEDTECH / NEOLYNC / LUXSLAM | RG520F-JO(SDX65)  | TBD                      | uart✅ usb❌(doesn’t expose any port)                | No❌, uart console locked    | LOCKED on latest FW                                                                                                          |
| JODU52240 | Arcadyan                      | RG520F-JO(SDX65)  | TBD                      | uart❓ usb❓                                         | Not yet, Unconfirmed❓       | Latest FW updates have disabled the web UI abilities.                                                                        |
| JODU52540 |                               |                   | JODU52540_REL_25_01_05_S | uart❓ usb❓                                         | Not yet, Unconfirmed❓       |                                                                                                                              |
#### TBD: To be determined yet 


## Firmware links

| Firmware ID        | V2.0.9                                                                                | V2.0.16                                                            |
| ------------------ | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| ARCNJIO_JIDU6101_R | [Download](https://mega.nz/file/jwIgRKYR#--QU1QC0MsjTGuY_jh0NIB0XVuEL5Qh7fsrgT34bGCM) |                                                                    |
| GMOBJIO_JIDU6801_R | [Download](https://mega.nz/file/KgxGyBiD#Dp_WtubqyFGhrk33rYGgdKgQUw7ax0FmUHaisNYmyd8) | [Download](https://mega.nz/folder/b8gkEZqL#jnUCRPWReJPH0X80IM1cXQ) |
| SPEDJIO_JIDU6601_R | [Download](https://mega.nz/file/LoZRXY7I#AGr7fBJDbpa0dLXrL-bAdALjEBgAT1wVzL7ncA0RJq8) |                                                                    |
| SRCMJIO_JIDU6401_R | [Download](https://mega.nz/file/vshSXRBS#kBpW7ls7Y2GJ7Y47DmgzzHNd-OCBSEBUoMblwyovp_E) |                                                                    |
| SKYWJIO_JIDU6701_R | [Download](https://mega.nz/file/v4YgBTTB#btKP77FlbvokfYR0mmBQCQEtCoLaAkIqjt7SpdKoiBI) |                                                                    |

| Firmware ID              | Links                                                                                 | Notes                    |
| ------------------------ | ------------------------------------------------------------------------------------- | ------------------------ |
| JODU52041_REL_02_32_00_S | [Download](https://mega.nz/file/v4By0aST#Tme3W2k8VCRAB7b99L1wI0NVxwrBHB0_bJ51Ck2i0JQ) | ❌Locked FW, DO NOT FLASH |
