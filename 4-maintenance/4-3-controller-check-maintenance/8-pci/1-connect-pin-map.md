# 4.3.8.1 커넥터 핀 맵

통신에 사용하는 커넥터의 핀 구성은 PCB 통신 카드에 따라 다릅니다.

![&#xADF8;&#xB9BC; 46 RJ45 &#xC18C;&#xCF13;&#xC758; &#xC774;&#xB354;&#xB137; &#xD540; &#xD560;&#xB2F9;](../../../.gitbook/assets/image127.png)

<table>
  <thead>
    <tr>
      <th style="text-align:center"><b>&#xBC88;&#xD638;</b>
      </th>
      <th style="text-align:center"><b>&#xC2E0;&#xD638;</b>
      </th>
      <th style="text-align:left"><b>                                                                       &#xC124;&#xBA85;</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">1</td>
      <td style="text-align:center">TX+</td>
      <td style="text-align:left">Transmit data +</td>
    </tr>
    <tr>
      <td style="text-align:center">2</td>
      <td style="text-align:center">TX-</td>
      <td style="text-align:left">Transmit data -</td>
    </tr>
    <tr>
      <td style="text-align:center">3</td>
      <td style="text-align:center">RX+</td>
      <td style="text-align:left">Receive data +</td>
    </tr>
    <tr>
      <td style="text-align:center">4</td>
      <td style="text-align:center">Term1</td>
      <td style="text-align:left">
        <p>Connected to each other and terminated to PE through RC circuit</p>
        <p>(Bob Smith Termination)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:center">5</td>
      <td style="text-align:center">Term1</td>
      <td style="text-align:left">
        <p>Connected to each other and terminated to PE through RC circuit</p>
        <p>(Bob Smith Termination)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:center">6</td>
      <td style="text-align:center">RX-</td>
      <td style="text-align:left">Receive data -</td>
    </tr>
    <tr>
      <td style="text-align:center">7</td>
      <td style="text-align:center">Term2</td>
      <td style="text-align:left">
        <p>Connected to each other and terminated to PE through RC circuit</p>
        <p>(Bob Smith Termination)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:center">8</td>
      <td style="text-align:center">Term2</td>
      <td style="text-align:left">
        <p>Connected to each other and terminated to PE through RC circuit</p>
        <p>(Bob Smith Termination)</p>
      </td>
    </tr>
  </tbody>
</table>

![&#xADF8;&#xB9BC; 47 CC-&#xB9C1;&#xD06C; &#xC778;&#xD130;&#xD398;&#xC774;&#xC2A4;\(CombiCon male &#xCEE4;&#xB125;&#xD130;, 5&#xD540;\)](../../../.gitbook/assets/image128.png)

| **호** | **신호** |                                                                   **설명** |
| :---: | :---: | :--- |
| 1 | DA | Data A |
| 2 | DB | Data B |
| 3 | DG | Data Ground |
| 4 | SLD | Shield |
| 5 | FG | Field Ground |

![&#xADF8;&#xB9BC; 48  DevcieNet &#xC778;&#xD130;&#xD398;&#xC774;&#xC2A4;\(CombiCon male &#xCEE4;&#xB125;&#xD130;, 5 &#xD540;\)](../../../.gitbook/assets/image129.png)

| **호** | **신호** |                                                                  **설명** |
| :---: | :---: | :--- |
| 1 | V- | Reference potential DeviceNet supply voltage |
| 2 | CAN\_L | CAN Low-Signal |
| 3 | Drain | Shield |
| 4 | CAN\_H | CAN High-Signal |
| 5 | V+ | +24 V DeviceNet supply voltage |

![&#xADF8;&#xB9BC; 49 PROFIBUS &#xC778;&#xD130;&#xD398;&#xC774;&#xC2A4;\(DSub female &#xCEE4;&#xB125;&#xD130;, 9 &#xD540;\)](../../../.gitbook/assets/image130.png)



| **번호** | **신호** |                                                                **설명** |
| :---: | :---: | :--- |
| 3 | RxD/TxD-P | Receive/Send Data-P respectively connection B plug |
| 5 | DGND | Reference potential |
| 6 | VP | Positive supply voltage |
| 8 | RxD/TxD-N | Receive/Send Data-N respectively connection A plug |

