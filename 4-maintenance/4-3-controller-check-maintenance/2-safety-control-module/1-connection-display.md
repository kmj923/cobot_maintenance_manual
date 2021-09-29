# 4.3.2.1 Connection and display

The connector layout, usages, and connecting devices used by the SCM are as follows:

|  |
| :--- |


![Figure 28 Safety control board \(BD6F1\)](../../../.gitbook/assets/image109.png)

<table>
  <thead>
    <tr>
      <th style="text-align:center"><b>Connector</b>
      </th>
      <th style="text-align:left"><b>                                       Usage</b>
      </th>
      <th style="text-align:center"><b>External connecting device</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">CNPS1, 2</td>
      <td style="text-align:left">
        <p>Power input for the safety circuit, 24 V DC</p>
        <p>(Channels 1 and 2)</p>
      </td>
      <td style="text-align:center">Power supply (SMPS2)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNCAN1</td>
      <td style="text-align:left">Data communication (exchange of torque data) with the torque sensors (Channel
        1) of the mechanical parts</td>
      <td style="text-align:center">Robot cable connection terminal (CNM)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNCAN2</td>
      <td style="text-align:left">Data communication (exchange of torque and position data) with the torque
        sensors (Channel 2) and encoder (Channel 2) of the mechanical parts</td>
      <td
      style="text-align:center">Robot cable connector (CNM)</td>
    </tr>
    <tr>
      <td style="text-align:center">RJ1</td>
      <td style="text-align:left">EtherCAT communication port</td>
      <td style="text-align:center">Robot cable connector (CNM)</td>
    </tr>
    <tr>
      <td style="text-align:center">RJ2</td>
      <td style="text-align:left">EtherCAT communication port</td>
      <td style="text-align:center">Microcomputer module (miniH6COM)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNPM1</td>
      <td style="text-align:left">Power input for driving motors of the mechanical parts (48 V DC)</td>
      <td
      style="text-align:center">Power supply (SMPS1)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNPM2</td>
      <td style="text-align:left">Power output for driving motors of the mechanical parts (48 V DC)</td>
      <td
      style="text-align:center">Robot cable connector (CNM)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNPM3</td>
      <td style="text-align:left">Power output for charging the motor driving power lines (48 V DC)</td>
      <td
      style="text-align:center">Power precharge module (PPM)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNEP1</td>
      <td style="text-align:left">Power input for charging the motor driving power lines (48 V DC)</td>
      <td
      style="text-align:center">Safety control module (SCM)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNRDM</td>
      <td style="text-align:left">Exchange of information on the state of regenerative discharge action</td>
      <td
      style="text-align:center">Regenerative discharge module (RDM)</td>
    </tr>
    <tr>
      <td style="text-align:center">CNPC2</td>
      <td style="text-align:left">Power input for I/O</td>
      <td style="text-align:center">Power supply (SMPS2)</td>
    </tr>
    <tr>
      <td style="text-align:center">TBSYS1</td>
      <td style="text-align:left">Input for the emergency stop switch and protective stop switch (safeguard),
        control of power charging function, and connection of monitoring signals</td>
      <td
      style="text-align:center">External safety switch, power precharge module (PPM)</td>
    </tr>
    <tr>
      <td style="text-align:center">TBSDO</td>
      <td style="text-align:left">Connection of safety output signals</td>
      <td style="text-align:center">Safety device</td>
    </tr>
    <tr>
      <td style="text-align:center">TBSDI</td>
      <td style="text-align:left">Connection of safety input signals</td>
      <td style="text-align:center">Safety device</td>
    </tr>
    <tr>
      <td style="text-align:center">TBAIO</td>
      <td style="text-align:left">Connection of general analog I/O signals</td>
      <td style="text-align:center">General analog devices</td>
    </tr>
    <tr>
      <td style="text-align:center">TBDIO</td>
      <td style="text-align:left">Connection of general digital I/O signals</td>
      <td style="text-align:center">General digital devices</td>
    </tr>
    <tr>
      <td style="text-align:center">RS485_1, 2</td>
      <td style="text-align:left">
        <p>Connection of RS-485 serial communication</p>
        <p>(reserved function)</p>
      </td>
      <td style="text-align:center">-</td>
    </tr>
    <tr>
      <td style="text-align:center">RS232_1, 2</td>
      <td style="text-align:left">
        <p>Connection of RS-232 serial communication</p>
        <p>(reserved function)</p>
      </td>
      <td style="text-align:center">-</td>
    </tr>
  </tbody>
</table>



