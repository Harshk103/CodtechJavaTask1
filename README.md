Name: Harsh Kashyap
Company: CODTECH IT SOLUTIONS PVT.LTD
ID:  CT4JP2647
Domain: Java Programming
Duration: June 20, 2024 to July 20, 2024.

Overview of Task-01: Designing a basic calculator.

First, we ask the user for input. The user has to choose from 5 basic mathematical operators i.e. addition '+', subtraction '-', multiplication '*', division (quotient) '/', modulo (remainder) '%'.
As soon as the input is received, the code sends the command to the switch block which receives character as its argument. It then sends the control to that part of the switch block which matches with the corresponding case. As soon as any of the cases match with the input given by the user, only those underlying lines of code executes and the control comes out of the switch block when all the lines have been executed and the control reaches break keyword at the end of the particular case. 

The keyword break prevents fall through i.e. it allows only one case (one operation) to operate at one time. If the character given by the user as an input fails to match the aforementioned 5 operators, then it also fails to match with any of the cases present in the switch block. In this scenario, the default case will operate to print the error message.
