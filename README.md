Download Link: https://assignmentchef.com/product/solved-cpe526-homework3-sequential-modeling-and-synthesis
<br>



Design an FSM circuit for control of lights used to start a race, which works as follows.

<table width="139">

 <tbody>

  <tr>

   <td width="96">Inputs:</td>

   <td width="43">ResetStartClock </td>

  </tr>

  <tr>

   <td width="96">Outputs:</td>

   <td width="43">RedYellowGreen</td>

  </tr>

 </tbody>

</table>




<ul>

 <li>Only one light can be on at any time.</li>

 <li>The Reset signal forces the circuit into a state in which the red light is turned on.</li>

 <li>When the Start signal is activated, the red light stays on for at least one second, then the yellow light is turned on.</li>

 <li>The yellow light stays turned on one second and then the green light is turned on.</li>

 <li>The green light stays on for at least three seconds and then the red light is turned on and the circuit returns to its reset state.</li>

 <li>The input clock runs at 10 MHz.</li>

</ul>




<ul>

 <li>Write a behavioral VHDL model of a clock divider that takes the 10 MHz clock and derives from it a 1 Hz clock.</li>

 <li>Write a behavioral VHDL model of the FSM.</li>

 <li>Write a testbench that reads input values from a text file (provided by me) to exercise the model. This testbench needs to incorporate your clock divider circuit and your finite state machine. It will respond to the slow clock and the text file will have inputs applied at every second.</li>

 <li>Simulate to verify the correctness of your model.</li>

 <li>Synthesize your design and write out .vho and .sdo files.</li>

 <li>Simulate the output from synthesis to verify the synthesized version.</li>

</ul>




Turn in your VHDL source files (both .vhd and .vho) and your SDF files.





