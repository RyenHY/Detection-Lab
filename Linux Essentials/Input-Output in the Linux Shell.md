# Input/Output in the Linux Shell

## Objective

To use the echo command to examine how input is received and how output is returned in the shell. Also use the expr command to further explore input and output while performing some basic calculations in the shell.

### Skills Learned

- echo command to generate some output in the shell
- expr command to perform basic mathematical calculations
- clear command to clear the Bash shell window

### Tools Used

- BASH shell

## Steps

**1)** **<ins>Generate output with the echo command</ins>**  

The echo command in the Bash shell outputs a specified string of text. The command echo hello is the input to the shell, and hello is the output from the shell.
<br/>   
*Fig 1: echo Hello* 
![image](https://github.com/RyenHY/Linux/assets/161639514/d307958e-f11c-4fba-8606-f47459e2b7ff)
<br/><br/>
*Fig 2: echo "Hello"*
![image](https://github.com/RyenHY/Linux/assets/161639514/01c62b0a-56fc-41cd-8bd9-5878b823a8a9)
<br/><br/>
**NOTE:** The quotation marks are optional in this case, but they tell the shell to group a series of characters together. This can be useful if you need to pass a string that contains certain characters that might be otherwise misinterpreted by the command.
<br/><br/>

**2)** **<ins>Generate output with the expr command</ins>**  

The expr command performs basic mathematical calculations and can be useful when you need to quickly perform a calculation
<br/><br/>
*Fig 3: expr Subtraction* 
![image](https://github.com/RyenHY/Linux/assets/161639514/5e71347f-bbf7-4e0f-bacd-a12b1ccd2171)
<br/><br/>
*Fig 4: expr Multiply* 
![image](https://github.com/RyenHY/Linux/assets/161639514/41e9f6a9-a806-49d3-9d74-8365cccd7853)
<br/><br/>
**NOTE:** The expr command requires that all terms and operators in an expression are separated by spaces. For example: expr 32 - 8, and not expr 32-8.
<br/><br/>

**3)** **<ins>Clear the Bash shell</ins>**  
<br/>
*Fig 5: clear BASH shell* 
![image](https://github.com/RyenHY/Linux/assets/161639514/068cf705-fe70-4d99-af6d-b2cdcf9a615f)
<br/><br/>
**NOTE:** Ctrl+L is a shortcut that does the same

