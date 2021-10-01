# 3.3.2.5 D-SUB 9 커넥터\(COM1, COM2\): 직렬 통신\(RS485, 422\)

D-SUB 24커넥터\(SDIO\)를 통하여 외부로 통신용 케이블 2포트를 연결할 수 있습니다. 신호 연결에 대한 자세한 내용은 “[**4.3.5 소형 컴퓨터 모듈**](../../../4-maintenance/4-3-controller-check-maintenance/5-microcomputer-module.md)”을 참조하십시오.

![](../../../.gitbook/assets/d-sub9.png)

\* 제어기 내부\(miniH6COM COM1, COM2\) / \* n=1, 2 \(COM 포트 번호\)

<table>
  <thead>
    <tr>
      <th style="text-align:center">&#xD540; &#xBC88;&#xD638;</th>
      <th style="text-align:center">1</th>
      <th style="text-align:center">2</th>
      <th style="text-align:center">3</th>
      <th style="text-align:center">4</th>
      <th style="text-align:center">5</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">&#xC81C;&#xC5B4;&#xAE30; &#xB0B4;&#xBD80;</td>
      <td style="text-align:center">1</td>
      <td style="text-align:center">2</td>
      <td style="text-align:center">3</td>
      <td style="text-align:center">4</td>
      <td style="text-align:center">5</td>
    </tr>
    <tr>
      <td style="text-align:center">&#xBA85;&#xCE6D;</td>
      <td style="text-align:center">
        <p>COMn_422_485</p>
        <p>_TX-</p>
      </td>
      <td style="text-align:center">
        <p>COMn_422_485</p>
        <p>_TX+</p>
      </td>
      <td style="text-align:center">
        <p>COMn_422</p>
        <p>_RX+</p>
      </td>
      <td style="text-align:center">
        <p>COMn_422</p>
        <p>_RX-</p>
      </td>
      <td style="text-align:center">GND</td>
    </tr>
  </tbody>
</table>

| 번호 | 6 | 7 | 8 | 9 | - |
| :---: | :---: | :---: | :---: | :---: | :--- |
| 제어기 내부 | 6 | 7 | 8 | 9 | - |
| 명칭 | COMn\_DSR\# | COMn\_RTS\# | COMn\_CTS\# | COMn\_RI\_V\# | - |

