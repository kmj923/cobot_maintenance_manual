# 4.3.1 내부 구조

제어기의 구조와 각 부분의 이름을 알아 두면 설치 및 유지 보수 방법을 확인할 때 유용합니다.

![&#xADF8;&#xB9BC; 25 &#xC81C;&#xC5B4;&#xAE30; &#xB0B4;&#xBD80; &#xAD6C;&#xC870;](../../.gitbook/assets/image107.png)

<table>
  <thead>
    <tr>
      <th style="text-align:center"><b>&#xBC88;&#xD638;</b>
      </th>
      <th style="text-align:center"><b>&#xC774;&#xB984;</b>
      </th>
      <th style="text-align:center">&lt;b&gt;&lt;/b&gt;</th>
      <th style="text-align:left"><b>                                                 &#xC124;&#xBA85;</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/1.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">
        <p>&#xC18C;&#xD615; &#xCEF4;&#xD4E8;&#xD130;</p>
        <p>&#xBAA8;&#xB4C8;</p>
      </td>
      <td style="text-align:center">miniH6COM</td>
      <td style="text-align:left">&#xD611;&#xB3D9;&#xB85C;&#xBD07; &#xC804;&#xBC18;&#xC744; &#xC81C;&#xC5B4;&#xD569;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/2.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">
        <p>&#xC804;&#xC6D0; &#xC2A4;&#xC704;&#xCE58;</p>
        <p>&#xBC0F; &#xCC28;&#xB2E8;&#xAE30;</p>
      </td>
      <td style="text-align:center">CP1</td>
      <td style="text-align:left">&#xC81C;&#xC5B4;&#xAE30;&#xC758; &#xC8FC;&#xC804;&#xC6D0;&#xC744; &#xCF1C;&#xAC70;&#xB098;
        &#xB055;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/3.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">&#xB178;&#xC774;&#xC988; &#xD544;&#xD130;</td>
      <td style="text-align:center">NF1</td>
      <td style="text-align:left">&#xC804;&#xB3C4;&#xC131; &#xB178;&#xC774;&#xC988;&#xB97C; &#xCC28;&#xB2E8;&#xD558;&#xB294;
        &#xD544;&#xD130;&#xC785;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/4.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">&#xBC84;&#xD37C;</td>
      <td style="text-align:center">BUFFER</td>
      <td style="text-align:left">&#xC815;&#xC804; &#xC2DC; &#xC77C;&#xC815; &#xC2DC;&#xAC04; &#xB3D9;&#xC548;
        &#xC18C;&#xD615; &#xCEF4;&#xD4E8;&#xD130; &#xBAA8;&#xB4C8;&#xC5D0; &#xC804;&#xB825;&#xC744;
        &#xACF5;&#xAE09;&#xD569;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/5.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">&#xC804;&#xC6D0; &#xC7A5;&#xCE58;2</td>
      <td style="text-align:center">SMPS2</td>
      <td style="text-align:left">&#xC870;&#xC778;&#xD2B8; &#xC561;&#xCD94;&#xC5D0;&#xC774;&#xD130;&#xC5D0;&#xC11C;
        &#xC0AC;&#xC6A9;&#xD558;&#xB294; &#xC804;&#xC6D0;(DC48V)&#xC744; &#xC0DD;&#xC131;&#xD569;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/6.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">&#xC804;&#xC6D0; &#xC7A5;&#xCE58;1</td>
      <td style="text-align:center">SMPS1</td>
      <td style="text-align:left">&#xC81C;&#xC5B4;&#xC6A9; &#xC804;&#xC6D0;(DC48V)&#xC744; &#xC0DD;&#xC131;&#xD569;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/7.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">
        <p>&#xD68C;&#xC0DD; &#xBC29;&#xC804;</p>
        <p>&#xBAA8;&#xB4C8;</p>
      </td>
      <td style="text-align:center">RDM</td>
      <td style="text-align:left">&#xC870;&#xC778;&#xD2B8; &#xC561;&#xCD94;&#xC5D0;&#xC774;&#xD130;&#xC758;
        &#xBAA8;&#xD130;&#xC5D0;&#xC11C; &#xBC1C;&#xC0DD;&#xD558;&#xB294; &#xD68C;&#xC0DD;
        &#xC804;&#xB825;&#xC744; &#xBC29;&#xC804;&#xD569;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/8.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">
        <p>&#xC548;&#xC804; &#xC81C;&#xC5B4;</p>
        <p>&#xBAA8;&#xB4C8;</p>
      </td>
      <td style="text-align:center">SCM</td>
      <td style="text-align:left">&#xD611;&#xB3D9;&#xB85C;&#xBD07;&#xC758; &#xC548;&#xC804; &#xAE30;&#xB2A5;&#xC744;
        &#xC81C;&#xC5B4;&#xD569;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:center">
        <img src="../../.gitbook/assets/9.png" alt="Adobe Systems" />
      </td>
      <td style="text-align:center">
        <p>&#xC804;&#xC6D0; &#xCDA9;&#xC804;</p>
        <p>&#xBAA8;&#xB4C8;</p>
      </td>
      <td style="text-align:center">PPM</td>
      <td style="text-align:left">&#xD611;&#xB3D9;&#xB85C;&#xBD07;&#xC5D0; &#xB0B4;&#xC7A5;&#xB41C; &#xC870;&#xC778;&#xD2B8;
        &#xC561;&#xCD94;&#xC5D0;&#xC774;&#xD130;&#xC758; &#xBAA8;&#xD130;&#xC6A9;
        &#xC804;&#xC6D0;&#xC744; &#xBBF8;&#xB9AC; &#xCDA9;&#xC804;&#xD569;&#xB2C8;&#xB2E4;.</td>
    </tr>
  </tbody>
</table>

