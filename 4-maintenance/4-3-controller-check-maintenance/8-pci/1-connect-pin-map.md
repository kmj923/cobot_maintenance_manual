# 4.3.8.1 Connect pin map

The pin composition of communication connectors varies depending on PCI communication cards.

![Figure 47 Ethernet pin assignments of RJ45 sockets](../../../.gitbook/assets/image127.png)

<table>
  <thead>
    <tr>
      <th style="text-align:center"><b>No</b>
      </th>
      <th style="text-align:center"><b>Signal</b>
      </th>
      <th style="text-align:left"><b>                                                </b>Description</th>
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

![Figure 48 CC-link interface \(CombiCon male connector, 5-pin\)](../../../.gitbook/assets/image128.png)

| **No** | **Signal** |                                             ****Description |
| :---: | :---: | :--- |
| 1 | DA | Data A |
| 2 | DB | Data B |
| 3 | DG | Data Ground |
| 4 | SLD | Shield |
| 5 | FG | Field Ground |

![Figure 49 DeviceNet interface \(CombiCon male connector, 5-pin\)](../../../.gitbook/assets/image129.png)

| **No** | **Signal** |                                             ****Description |
| :---: | :---: | :--- |
| 1 | V- | Reference potential DeviceNet supply voltage |
| 2 | CAN\_L | CAN Low-Signal |
| 3 | Drain | Shield |
| 4 | CAN\_H | CAN High-Signal |
| 5 | V+ | +24 V DeviceNet supply voltage |

![Figure 50 PROFIBUS interface \(Dsub female connector, 9-pin](../../../.gitbook/assets/image130.png)

| **No** | **Signal** |                                          ****Description |
| :---: | :---: | :--- |
| 3 | RxD/TxD-P | Receive/Send Data-P respectively connection B plug |
| 5 | DGND | Reference potential |
| 6 | VP | Positive supply voltage |
| 8 | RxD/TxD-N | Receive/Send Data-N respectively connection A plug |

