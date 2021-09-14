# 4.3.5 소형 컴퓨터 모듈

소형 컴퓨터 모듈\(miniH6COM, EBC-GF53\)은 Hi6제어 플랫폼을 기반으로 협동로봇을 구동하고 제어하는 모듈입니다. 이 모듈에 대한 자세한 내용은 “**Hi6 제어기 조작 설명서**”를 참조하십시오.

소형 컴퓨터 모듈의 외부 인터페이스와 COM 포트, 전원 커넥터의 구성은 다음과 같습니다.



|  |
| :--- |


![&#xADF8;&#xB9BC; 39 &#xC18C;&#xD615; &#xCEF4;&#xD4E8;&#xD130; &#xBAA8;&#xB4C8; &#xC678;&#xBD80; &#xC778;&#xD130;&#xD398;&#xC774;&#xC2A4;](../../.gitbook/assets/image121.png)

<table>
  <thead>
    <tr>
      <th style="text-align:center"><b>&#xD3EC;&#xD2B8;</b>
      </th>
      <th style="text-align:center"><b>&#xC6A9;&#xB3C4;</b>
      </th>
      <th style="text-align:center"><b>&#xC0AC;&#xC591;</b>
      </th>
      <th style="text-align:center"><b>&#xAC1C;&#xC218;</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">DP</td>
      <td style="text-align:center">&#xB514;&#xC2A4;&#xD50C;&#xB808;&#xC774;</td>
      <td style="text-align:center">Display Port</td>
      <td style="text-align:center">1</td>
    </tr>
    <tr>
      <td style="text-align:center">LAN1, LAN2, LAN3</td>
      <td style="text-align:center">&#xC720;&#xC120; &#xB79C;</td>
      <td style="text-align:center">Giga LAN</td>
      <td style="text-align:center">3</td>
    </tr>
    <tr>
      <td style="text-align:center">USB1, USB2</td>
      <td style="text-align:center">USB</td>
      <td style="text-align:center">USB2.0</td>
      <td style="text-align:center">2</td>
    </tr>
    <tr>
      <td style="text-align:center">COM1, COM2</td>
      <td style="text-align:center">&#xC9C1;&#xB82C; &#xD1B5;&#xC2E0;</td>
      <td style="text-align:center">RS-232/422/485</td>
      <td style="text-align:center">2</td>
    </tr>
    <tr>
      <td style="text-align:center">GPIO</td>
      <td style="text-align:center">&#xB514;&#xC9C0;&#xD138; &#xC785;&#xCD9C;&#xB825;</td>
      <td style="text-align:center">8 bits, DSUB-9</td>
      <td style="text-align:center">1</td>
    </tr>
    <tr>
      <td style="text-align:center">DC IN</td>
      <td style="text-align:center">&#xC804;&#xC6D0; &#xC785;&#xB825;</td>
      <td style="text-align:center">DC12 ~ 24V, 10A</td>
      <td style="text-align:center">1</td>
    </tr>
    <tr>
      <td style="text-align:center">-</td>
      <td style="text-align:center">&#xD655;&#xC7A5; &#xC2AC;&#xB86F;</td>
      <td style="text-align:center">PCIe x1, PCI</td>
      <td style="text-align:center">
        <p>2</p>
        <p>
          <img src="../../.gitbook/assets/image122.png" alt="&#xADF8;&#xB9BC; 40 COM &#xD3EC;&#xD2B8;(Male) &#xD540; &#xB9F5;"
          />
        </p>
      </td>
    </tr>
  </tbody>
</table>

![&#xADF8;&#xB9BC; 40 COM &#xD3EC;&#xD2B8;\(Male\) &#xD540; &#xB9F5;](../../.gitbook/assets/image122.png)

| **번호** | **이름** | **번호** | **이름** |
| :---: | :---: | :---: | :---: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | COMn\_422\_485\_TX- | ![Adobe Systems](../../.gitbook/assets/6.png) | COMn\_DSR\# |
| ![Adobe Systems](../../.gitbook/assets/2.png) | COMn\_422\_485\_TX+ | ![Adobe Systems](../../.gitbook/assets/7.png) | COMn\_RTS\# |
| ![Adobe Systems](../../.gitbook/assets/3.png) | COMn\_422\_RX+ | ![Adobe Systems](../../.gitbook/assets/8.png) | COMn\_CTS\# |
| ![Adobe Systems](../../.gitbook/assets/4.png) | COMn\_422\_RX- | ![Adobe Systems](../../.gitbook/assets/9.png) | COMn\_RI\_V\# |
| ![Adobe Systems](../../.gitbook/assets/5.png) | GND |  |  |

![&#xADF8;&#xB9BC; 41 COM &#xD3EC;&#xD2B8;\(Female\) &#xD540; &#xB9F5;](../../.gitbook/assets/image123.png)

| **번호** | **이름** | **번호** | **이름** |
| :---: | :---: | :---: | :---: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | GPIO\_GPIO0 | ![Adobe Systems](../../.gitbook/assets/6.png) | GPIO\_GPIO4 |
| ![Adobe Systems](../../.gitbook/assets/2.png) | GPIO\_GPIO1 | ![Adobe Systems](../../.gitbook/assets/7.png) | GPIO\_GPIO5 |
| ![Adobe Systems](../../.gitbook/assets/3.png) | GPIO\_GPIO2 | ![Adobe Systems](../../.gitbook/assets/8.png) | GPIO\_GPIO6 |
| ![Adobe Systems](../../.gitbook/assets/4.png) | GPIO\_GPIO3 | ![Adobe Systems](../../.gitbook/assets/9.png) | GPIO\_GPIO7 |
| ![Adobe Systems](../../.gitbook/assets/5.png) | GND |  |  |



|  |
| :---: |


![&#xADF8;&#xB9BC; 42 DCIN \(&#xC804;&#xC6D0; &#xCEE4;&#xB125;&#xD130;\) &#xD540; &#xB9F5;](../../.gitbook/assets/image124.png)

| **번호** | **이름** |
| :---: | :---: |
| ![Adobe Systems](../../.gitbook/assets/1.png) | DC24V |
| ![Adobe Systems](../../.gitbook/assets/2.png) | FG |
| ![Adobe Systems](../../.gitbook/assets/3.png) | GND |



