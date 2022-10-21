# Data-Location-Assignment

In this assignment, there is an error in the code. When the original code is deployed, the balance does not show the most updated one even though more money is added. For example, when “200” is added to the original amount “100” with the button “updateBalance”, balance still shows that there is only “100” after clicking the “getBalance” button.

The solution is to simply replace “memory” with “storage”, because memory stores a function, and storage stores state variables, which can be altered. “user = users[id];” for updating balance is not a function, but it’s for storing state variables. 

Memory-assignment-template.sol is the original code with the error. 
Memory-assignment-done.sol is the code with the modification. 
