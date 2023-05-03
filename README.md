Download Link: https://assignmentchef.com/product/solved-cs39001-assignment2-verilog-design-of-binary-adders
<br>



<ol>

 <li><strong>[Ripple Carry Binary Adder] </strong>Design (using Verilog), simulate, and synthesize for any target FPGA supported by your version of <em>Vivado </em>an 8-bit <em>ripple carry adder</em>. Your design should consist of a cascade of eight full adders. Write a testbench to simulate it. After logic synthesis, note its hardware requirement and critical path delay from the synthesis report. The interface of your design should be:</li>

</ol>

module ripple carry adder (input [7:0] a, input [7:0] b, input cin, output [7:0] sum,

output cout);.                                                                                                                                                                 (5 marks)

<ol start="2">

 <li><strong>[Hybrid Binary Adder] </strong>Design (using Verilog), simulate, and synthesize for any target FPGA supported by your version of <em>Vivado</em>, an 8-bit <em>hybrid adder</em>. Your design should consist of a cascade of two 4-bit <em>carry lookahead adders</em>. Write a testbench to simulate it. After logic synthesis, note its hardware requirement and critical path delay from the synthesis report. The interface of your design should be:</li>

</ol>

module hybrid adder (input [7:0] a, input [7:0] b, input cin, output [7:0] sum, output

cout);.                                                                                                                                                                                (6 marks)

<ol start="3">

 <li><strong>[Bit-serial Binary Adder] </strong>Design (using Verilog), simulate and synthesize for any target FPGA supported by your version of <em>Vivado</em>, a bit-serial adder. Write a testbench to simulate it. After logic synthesis, note its hardware requirement and critical path delay from the synthesis report. The input-side shift registers used in the datpath of your bit-serial adder should have “parallel load” capabilities such that the 8-bit operands can be loaded in each of them in one clock cycle. Come up with a proper interface of your design, which includes all input control signals and a clock signal. (7 marks)</li>

 <li>Finally, submit a small 1-page report (in .pdf format) comparing the speed of operation and hardware requirements of the above three designs. This report should be inside the zipped folder you submit. (2 marks)</li>

</ol>