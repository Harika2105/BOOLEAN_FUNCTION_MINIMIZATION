# BOOLEAN_FUNCTION_MINIMIZATION

## **AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## **Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

## **Software – Quartus prime**

## **Theory**

## **Logic Diagram**

## **Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## **Program:**
```
module booleanfunction1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule

module booleanfuction2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule 
```

Developed by:S.HARIKA
RegisterNumber:24002063


## **RTL realization**

## **Output:**
### ![booleanfuction 1](https://github.com/user-attachments/assets/5ce71298-2b51-4bfa-9970-e122ede77ea4)

### ![booleanfunction2](https://github.com/user-attachments/assets/02bcd197-1148-4255-89c7-96063fef7283)

## **RTL**

## **Timing Diagram**
![booleanfunction wf](https://github.com/user-attachments/assets/64605eb1-a8c6-4ec1-ae0f-a624df5016cd)

## **Result:**
Thus the given logic functions are implemented using and their operations are verified using verilog programming.
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

