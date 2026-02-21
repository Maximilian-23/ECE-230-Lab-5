# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Maximilian Martinez & Aiden Smith

## Lab Summary
In this lab we had to code the top.v file, as well as modules a and b from scratch. We also had to modify the constraints file to only map the pins and leds to what we needed for the top and module files. We built module a to route into module b as an input, which then gave us the final output of the circuit. It was interesting and a good experience to have to build most of the files we used from scratch and gave us a better understanding of how to write code in Verilog.

## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file implements the modules a and b so then can be programmed onto the board.

### 2 - Explain the function of the Constraints file.
The constraints file maps the physical pins and leds to what is needed for the Verilog code.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
We originally thought that Circuit A should have been the Minterms because it is easy to see the 4 1's grouped right next to each other. After we completed the project, we realized the Maxterm function could have been simplified to an equation with the same number of gates as the Minterm function. Circuit B's Minterm and Maxterm functions would be the same number of gates, so only depends of if we wanted to find the SOP or the POS.
