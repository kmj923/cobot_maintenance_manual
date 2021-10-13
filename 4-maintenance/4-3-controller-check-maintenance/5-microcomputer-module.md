# 4.3.5 Microcomputer module

The microcomputer module (miniH6COM, EBC-GF53) drives and controls the collaborative robot based on the Hi6 control platform. For more details on this module, see “[**Operation Manual for Hi6 Controllers.**](https://hyundai-robotics.gitbook.io/hi6-operation-manual/v/op-english/)”

The composition of the external interface, COM ports, and power connector of the microcomputer module is as follows:



![Figure 40 External interface of the microcomputer module](../../.gitbook/assets/image121.png)

|     **Port**     |         Usage        |   Specification  | **Count** |
| :--------------: | :------------------: | :--------------: | :-------: |
|        DP        |        Display       |   Display Port   |     1     |
| LAN1, LAN2, LAN3 |       Wired LAN      |     Giga LAN     |     3     |
|    USB1, USB2    |          USB         |      USB2.0      |     2     |
|    COM1, COM2    | Serial communication |  RS-232/422/485  |     2     |
|       GPIO       |      Digital I/O     |  8 bits, DSUB-9  |     1     |
|       DC IN      |      Power input     | DC12 \~ 24V, 10A |     1     |
|         -        |    Extension slot    |   PCIe x1, PCI   |     2     |

![Figure 41 COM port (male) pin map](../../.gitbook/assets/image122.png)

|                     **No**                    |       **Name**      |                     **No**                    |  **Name**  |
| :-------------------------------------------: | :-----------------: | :-------------------------------------------: | :--------: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | COMn\_422\_485\_TX- | ![Adobe Systems](../../.gitbook/assets/6.png) |  COMn_DSR# |
| ![Adobe Systems](../../.gitbook/assets/2.png) | COMn\_422\_485\_TX+ | ![Adobe Systems](../../.gitbook/assets/7.png) |  COMn_RTS# |
| ![Adobe Systems](../../.gitbook/assets/3.png) |    COMn\_422\_RX+   | ![Adobe Systems](../../.gitbook/assets/8.png) |  COMn_CTS# |
| ![Adobe Systems](../../.gitbook/assets/4.png) |    COMn\_422\_RX-   | ![Adobe Systems](../../.gitbook/assets/9.png) | COMn_RI_V# |
| ![Adobe Systems](../../.gitbook/assets/5.png) |         GND         |                                               |            |

![Figure 42 COM port (female) pin map](../../.gitbook/assets/image123.png)

|                     **No**                    |  **Name**  |                     **No**                    |  **Name**  |
| :-------------------------------------------: | :--------: | :-------------------------------------------: | :--------: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | GPIO_GPIO0 | ![Adobe Systems](../../.gitbook/assets/6.png) | GPIO_GPIO4 |
| ![Adobe Systems](../../.gitbook/assets/2.png) | GPIO_GPIO1 | ![Adobe Systems](../../.gitbook/assets/7.png) | GPIO_GPIO5 |
| ![Adobe Systems](../../.gitbook/assets/3.png) | GPIO_GPIO2 | ![Adobe Systems](../../.gitbook/assets/8.png) | GPIO_GPIO6 |
| ![Adobe Systems](../../.gitbook/assets/4.png) | GPIO_GPIO3 | ![Adobe Systems](../../.gitbook/assets/9.png) | GPIO_GPIO7 |
| ![Adobe Systems](../../.gitbook/assets/5.png) |     GND    |                                               |            |



|     |
| :-: |

![Figure 43 DCIN (power connector) pin map](../../.gitbook/assets/image124.png)

|                     **No**                    | **Name** |
| :-------------------------------------------: | :------: |
| ![Adobe Systems](../../.gitbook/assets/1.png) |   DC24V  |
| ![Adobe Systems](../../.gitbook/assets/2.png) |    FG    |
| ![Adobe Systems](../../.gitbook/assets/3.png) |    GND   |

