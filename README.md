# skill-ass
### Aim: To Design and simulate 9 bit parity generator using Verilog.
### HARDWARE REQUIRED:  – PC, Cyclone II , USB flasher
### SOFTWARE REQUIRED:   Quartus prime
### THEORY 

### what is 9 bit parity generator?
 These universal 9-bit parity generators/checkers utilize advanced Schottky high-performance circuitry and feature odd (Σ ODD) and even (Σ EVEN) outputs to facilitate operation of either odd- or even-parity applications. The word-length capability is easily expanded by cascading.
 
 ![image](https://user-images.githubusercontent.com/123469171/215488063-e3e80bd3-1245-402c-b5f3-69f79dab3959.png)

### Procedure

/* write all the steps invloved */

### program

Program for parity generator and verify its truth table in quartus using Verilog programming.

Developed by: kabilan V

RegisterNumber: 22000284

9-Bit parity geneartor:
```
module parity(x,y,z,result);
input x,y,z;
output result;
xor (result,x,y,z); 
endmodule
```

RTL LOGIC

![Screenshot (15)](https://user-images.githubusercontent.com/123469171/215491546-ab46f5bf-5f0d-4307-b570-0ac679359c36.png)

TIMING DIAGRAM

![Screenshot (16)](https://user-images.githubusercontent.com/123469171/215491820-18ba6ff7-c175-410d-82ce-a4631f7c69d5.png)

TRUTH TABLE

![Screenshot (17)](https://user-images.githubusercontent.com/123469171/215492334-8ca081e6-5372-4f40-806d-469c92509aef.png)


RESULT 

Thus the implementation of 9 bit parity generator using Verilog are verified.

