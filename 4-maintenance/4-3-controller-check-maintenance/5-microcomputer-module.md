# 4.3.5 소형 컴퓨터 모듈

소형 컴퓨터 모듈\(miniH6COM, EBC-GF53\)은 Hi6제어 플랫폼을 기반으로 협동로봇을 구동하고 제어하는 모듈입니다. 이 모듈에 대한 자세한 내용은 “**Hi6 제어기 조작 설명서**”를 참조하십시오.

소형 컴퓨터 모듈의 외부 인터페이스와 COM 포트, 전원 커넥터의 구성은 다음과 같습니다.



|  |
| :--- |


![&#xADF8;&#xB9BC; 40 &#xC18C;&#xD615; &#xCEF4;&#xD4E8;&#xD130; &#xBAA8;&#xB4C8; &#xC678;&#xBD80; &#xC778;&#xD130;&#xD398;&#xC774;&#xC2A4;](../../.gitbook/assets/image121.png)

| **포트** | **용도** | **사양** | **개수** |
| :---: | :---: | :---: | :---: |
| DP | 디스플레이 | Display Port | 1 |
| LAN1, LAN2, LAN3 | 유선 랜 | Giga LAN | 3 |
| USB1, USB2 | USB | USB2.0 | 2 |
| COM1, COM2 | 직렬 통신 | RS-232/422/485 | 2 |
| GPIO | 디지털 입출력 | 8 bits, DSUB-9 | 1 |
| DC IN | 전원 입력 | DC12 ~ 24V, 10A | 1 |
| - | 확장 슬롯 | PCIe x1, PCI | 2 |

![&#xADF8;&#xB9BC; 41 COM &#xD3EC;&#xD2B8;\(Male\) &#xD540; &#xB9F5;](../../.gitbook/assets/image122.png)

| **번호** | **이름** | **번호** | **이름** |
| :---: | :---: | :---: | :---: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | COMn\_422\_485\_TX- | ![Adobe Systems](../../.gitbook/assets/6.png) | COMn\_DSR\# |
| ![Adobe Systems](../../.gitbook/assets/2.png) | COMn\_422\_485\_TX+ | ![Adobe Systems](../../.gitbook/assets/7.png) | COMn\_RTS\# |
| ![Adobe Systems](../../.gitbook/assets/3.png) | COMn\_422\_RX+ | ![Adobe Systems](../../.gitbook/assets/8.png) | COMn\_CTS\# |
| ![Adobe Systems](../../.gitbook/assets/4.png) | COMn\_422\_RX- | ![Adobe Systems](../../.gitbook/assets/9.png) | COMn\_RI\_V\# |
| ![Adobe Systems](../../.gitbook/assets/5.png) | GND |  |  |

![&#xADF8;&#xB9BC; 42 COM &#xD3EC;&#xD2B8;\(Female\) &#xD540; &#xB9F5;](../../.gitbook/assets/image123.png)

| **번호** | **이름** | **번호** | **이름** |
| :---: | :---: | :---: | :---: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | GPIO\_GPIO0 | ![Adobe Systems](../../.gitbook/assets/6.png) | GPIO\_GPIO4 |
| ![Adobe Systems](../../.gitbook/assets/2.png) | GPIO\_GPIO1 | ![Adobe Systems](../../.gitbook/assets/7.png) | GPIO\_GPIO5 |
| ![Adobe Systems](../../.gitbook/assets/3.png) | GPIO\_GPIO2 | ![Adobe Systems](../../.gitbook/assets/8.png) | GPIO\_GPIO6 |
| ![Adobe Systems](../../.gitbook/assets/4.png) | GPIO\_GPIO3 | ![Adobe Systems](../../.gitbook/assets/9.png) | GPIO\_GPIO7 |
| ![Adobe Systems](../../.gitbook/assets/5.png) | GND |  |  |



|  |
| :---: |


![&#xADF8;&#xB9BC; 43 DCIN \(&#xC804;&#xC6D0; &#xCEE4;&#xB125;&#xD130;\) &#xD540; &#xB9F5;](../../.gitbook/assets/image124.png)

| **번호** | **이름** |
| :---: | :---: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | DC24V |
| ![Adobe Systems](../../.gitbook/assets/2.png) | FG |
| ![Adobe Systems](../../.gitbook/assets/3.png) | GND |



