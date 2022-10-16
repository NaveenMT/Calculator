# Calculator
java program


it is a simple java program
arithmetic calculator
it performs addition, subtraction, multiplication and division based on BODMAS rule
all oops concepts included


1. it get a arithmetic operations with operands as a string upto some range 
     for example,
          12/23*12-10
     1.1.  if we give a wrong string or missing the operands in a string then it throws a error
            for example,
                  12/12+*10
                  ---> syntax error
2.  it splits the string as a tokens using the operators
3.  it parces all the operand tokens as a floot value
4. it performs the operation based on BODMAS rules
5.  if the output part ends with .0 then it returns a whole values else it returns float values
        for example,
            1)  12.0
                  -->12
            2)  12.0012
                  -->12.0012
