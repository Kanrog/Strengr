<h1><span style="text-decoration: underline;">Strengr</span></h1>
<h3>A simple extender for most printer electronics.</h3>
<p><img src="https://github.com/Kanrog/Strengr/blob/main/RENDER.png" alt="" width="350" /></p>
<blockquote>
<p><em>First of, a little disclaimer: This product involves changing the electronics of your printer, do this at your own risk, we are not responsible for any damages that might occur.</em></p>
</blockquote>
<p>&nbsp;</p>
<p>Strengr <em>(Old-norse word for "Rope")</em>, was created by Kanrog and Automated Neurotic.</p>
<p>The Idea behind this project was to make an easy solution for those who want to move all the electronics on their printer away from it, usually to enclose the printer.</p>
<p>The Strengr is simply a pass-trough terminal, there is no circuitry on the board, it simply rewires all the pins into 2x <span style="text-decoration: underline;">DVI-I Dual Link</span> cables to make extending easier.<br />Due to limitations in the DVI-I cables themselves, we do not recomment powering any of your heaters trough it, and we have included 3x screw terminal power-passtroughs for this purpose.</p>
<p>Instead of extending all the wires, soldering, re-pinning, etc, simply plug them into one of the Strengr boards, connect 2 DVI cables and the heater wires, then connect another Strengr board on the other end.</p>
<blockquote>
<p><span style="text-decoration: underline;">There are limitations to this design, the main one being power delivery to the steppers, we have set a max current draw of 1.5A, we do not recommend going any higher.</span></p>
</blockquote>
<p>The strengr board is identical at both ends, meaning the USB-A plugs are also the same. We recommend aquiring a pair of USB-A male-male cables to connect to the board.<br /><br />Please note that the pinout on the board is just a suggestion, you can use any pin for whatever you want.<br />As an example, if you are not using the CAN connector, you have an extra connector you can use for other things, like the thermistor on your hotend.</p>
<p><span style="color: ##e62e00;">There as a smal caveat to this, the PROBE, ENDSTOPS and FILAMENT RUNOUT SENSOR all share the 5v pin.</span>.</p>
<table style="width: 230px;">
<tbody>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;"><span style="text-decoration: underline;"><strong>In/output</strong></span></td>
<td style="height: 13px; width: 87px;"><span style="text-decoration: underline;"><strong>Amount</strong></span></td>
<td style="height: 13px; width: 87px;"><span style="text-decoration: underline;"><strong>Connector</strong></span></td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">Stepper-motor</td>
<td style="height: 13px; width: 87px;">6</td>
<td style="height: 13px; width: 87px;">4-pin JST-XH</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">Endstop</td>
<td style="height: 13px; width: 87px;">4</td>
<td style="height: 13px; width: 87px;">3-pin JST XH</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">Fan</td>
<td style="height: 13px; width: 87px;">3</td>
<td style="height: 13px; width: 87px;">2-pin JST XH</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">CAN/Thermistor</td>
<td style="height: 13px; width: 87px;">1</td>
<td style="height: 13px; width: 87px;">2-pin JST XH</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">Thermistor</td>
<td style="height: 13px; width: 87px;">1</td>
<td style="height: 13px; width: 87px;">2-pin JST XH</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">FIlament sensor</td>
<td style="height: 13px; width: 87px;">1</td>
<td style="height: 13px; width: 87px;">3-pin JST XH</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">Probe</td>
<td style="height: 13px; width: 87px;">1</td>
<td style="height: 13px; width: 87px;">5-pin JST XH</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">USB-A-IN</td>
<td style="height: 13px; width: 87px;">2</td>
<td style="height: 13px; width: 87px;">USB-A female</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">USB-A-OUT</td>
<td style="height: 13px; width: 87px;">2</td>
<td style="height: 13px; width: 87px;">USB-A female</td>
</tr>
<tr style="height: 13px;">
<td style="height: 13px; width: 123.4px;">Power pass trough</td>
<td style="height: 13px; width: 87px;">3</td>
<td style="height: 13px; width: 87px;">5mm Screw terminal</td>
</tr>
</tbody>
</table>
