# 4.3.4.1 Connection and display

The connector layout, usage, and connecting devices used by the RDM are as follows:

| Connector |                          **Usage** | External connecting device |
| :---: | :--- | :---: |
| CNPM3 | Connection of 48 V DC power line \(for the motor\)  | Power precharge module \(PPM\) CNPM3 |
| CNRDM | Connection of state information signals | Safety control module \(SCM\) CNPMD |

The details of the state display of the RDM are as follows:

<table>
  <thead>
    <tr>
      <th style="text-align:center"><b>LED</b>
      </th>
      <th style="text-align:left"><b>                         Usage</b>
      </th>
      <th style="text-align:center">Display details (lamp state)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">LED7</td>
      <td style="text-align:left">Detection of overheating of the regenerative discharge resistor or overcurrent
        of the discharge current</td>
      <td style="text-align:center">
        <p>Overheating of the regenerative discharge resistor (95&#xB0;C)
          <br />
        </p>
        <p>or Overcurrent of the discharge current (15 A)
          <br />
        </p>
        <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:center">LED8</td>
      <td style="text-align:left">Detection of disconnection of the regenerative discharge resistor</td>
      <td
      style="text-align:center">The regenerative discharge resistor is disconnected (displayed even during
        the regenerative discharge operation)</td>
    </tr>
    <tr>
      <td style="text-align:center">LED9</td>
      <td style="text-align:left">Detection of the regenerative discharge operation</td>
      <td style="text-align:center">Under regenerative discharge operation</td>
    </tr>
    <tr>
      <td style="text-align:center">LED10</td>
      <td style="text-align:left">Detection of regenerative discharge overtime</td>
      <td style="text-align:center">Occurrence of regenerative discharge operation for 10 ms or longer</td>
    </tr>
  </tbody>
</table>

