# Steer Module

IP = 192.168.5.126<br>
Hello = 126<br>
Port = 5126<br>
00 00 56 00 00 7E<br>


<table>
    <thead>
        <tr>
            <th nowrap align=center>PGN Name</th>
            <th nowrap align=center>Src</th>
            <th nowrap align=center>Dec</th>
            <th nowrap align=center>PGN</th>
            <th nowrap align=center>Dec</th>
            <th nowrap align=center>Len</th>
            <th nowrap align=center>Byte 5</th>
            <th nowrap align=center>Byte 6</th>
            <th nowrap align=center>Byte 7</th>
            <th nowrap align=center>Byte 8</th>
            <th nowrap align=center>Byte 9</th>
            <th nowrap align=center>Byte 10</th>
            <th nowrap align=center>Byte 11</th>
            <th nowrap align=center>Byte 12</th>
            <th nowrap align=center>Byte 13</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align=center>Steer Data</td>
            <td align=center>7F</td>
            <td align=center>127</td>
            <td align=center>FE</td>
            <td align=center>254</td>
            <td align=center>8</td>
            <td align=center colspan=2>Speed</td>
            <td align=center>Status</td>
            <td align=center colspan=2>steerAngle</td>
            <td align=center>xte</td>
            <td align=center>SC1to8</td>
            <td align=center>SC9to16</td>
            <td align=center>CRC</td>
        </tr>
        <tr>
            <td align=center>Steer Settings</td>
            <td align=center>7F</td>
            <td align=center>127</td>
            <td align=center>FC</td>
            <td align=center>252</td>
            <td align=center>8</td>
            <td align=center>gainP</td>
            <td align=center>highPWM</td>
            <td align=center>lowPWM</td>
            <td align=center>minPWM</td>
            <td align=center>countsPerDeg</td>
            <td align=center colspan=2>steerOffset</td>
            <td align=center>ackermanFix</td>
            <td align=center>CRC</td>
        </tr>
        <tr>
            <td align=center>Steer Config</td>
            <td align=center>7F</td>
            <td align=center>127</td>
            <td align=center>FB</td>
            <td align=center>251</td>
            <td align=center>8</td>
            <td align=center>set0</td>
            <td align=center>pulseCount</td>
            <td align=center>minSpeed</td>
            <td align=center>sett1</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>CRC</td>
        </tr>
        <tr>
            <td align=center>From AutoSteer</td>
            <td align=center>7E</td>
            <td align=center>126</td>
            <td align=center>FD</td>
            <td align=center>253</td>
            <td align=center>8</td>
            <td align=center colspan=2>ActualSteerAngle * 100</td>
            <td align=center colspan=2>IMU Heading Hi/Lo</td>
            <td align=center colspan=2>IMU Roll Hi/Lo</td>
            <td align=center>Switch</td>
            <td align=center>PWMDisplay</td>
            <td align=center>CRC</td>
        </tr>
        <tr>
            <td align=center>From Autosteer 2</td>
            <td align=center>7F</td>
            <td align=center>127</td>
            <td align=center>FA</td>
            <td align=center>250</td>
            <td align=center>8</td>
            <td align=center>Sensor Value</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>***</td>
            <td align=center>CRC</td>
        </tr>
    </tbody>
</table>
