# EXPERIMENT--01-ALP-FOR-8086

## Name : NETHRAA N

## Roll no : 212224040217

## Date of experiment : 29.10.2026





# Aim: To Write and execute ALP on fundamental arithmetic and logical operations
# Components required: 8086  emulator 
# Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


# Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







# Programs for arithmetic  operations

## Addition  of 16 bit ALP 

```
MOV AX,1234H
MOV BX,2345H
ADD AX,BX
HLT
```

## Output  


<img width="1919" height="1009" alt="image" src="https://github.com/user-attachments/assets/915eae7c-06be-4847-b4c0-3f5591e2a116" />


 
## Subtraction of 16 bit numbers  ALP 

```
MOV AX,5436H
MOV BX,8764H
SUB AX,BX
HLT
```
 
## Output  

<img width="1919" height="1013" alt="Screenshot 2026-10-29 182050" src="https://github.com/user-attachments/assets/5a769bcf-18bb-4abe-b37e-044febdfcb1b" />

## Multiplication of 16 bit numbers  ALP

```
MOV AX,356CH
MOV BX,467DH
MUL BX
HLT
```

## Output  

<img width="1919" height="1008" alt="Screenshot 2026-10-29 182153" src="https://github.com/user-attachments/assets/98352b24-cd02-430c-b3bf-81339577964d" />



## Division of 16 bit numbers  ALP 

```
MOV AX,5467H
MOV BX,2345H
DIV BX
HLT
```

## Output  

<img width="1919" height="1010" alt="Screenshot 2026-10-29 182605" src="https://github.com/user-attachments/assets/4454b8ec-1401-4f3f-8919-11baecef5ed8" />


# Programs for logical  operations

## AND of 16 bit numbers ALP

```
MOV BX,3527H
MOV CX,2968H
AND BX,CX
RET
```

## OUTPUT

<img width="1919" height="1005" alt="image" src="https://github.com/user-attachments/assets/12417201-7df4-4764-b573-ba9c39077032" />

## NAND of 16 bit numbers ALP

```
MOV BX,3527H
MOV CX,2968H
AND BX,CX
NOT BX
RET
```
## OUTPUT
<img width="1919" height="1003" alt="Screenshot 2026-10-29 184152" src="https://github.com/user-attachments/assets/ee76129d-50dd-45bc-84d6-4823ba996fdb" />


## OR of 16 bit numbers ALP

```
MOV BX,3527H
MOV CX,2968H
OR BX,CX 
RET
```

## OUTPUT

<img width="1919" height="1005" alt="image" src="https://github.com/user-attachments/assets/9b820121-5bd5-42d2-ae11-17a32e1f5e03" />

## NOR of 16 bit numbers ALP

```
MOV BX,3527H
MOV CX,2968H
OR BX,CX
NOT BX
RET
```

## OUTPUT

<img width="1919" height="1008" alt="Screenshot 2026-10-29 184544" src="https://github.com/user-attachments/assets/4e41636e-a569-4934-a13e-c209812f3172" />

## XOR of 16 bit numbers ALP

```
MOV BX,3527H
MOV CX,2968H
XOR BX,CX
RET
```

## OUTPUT

<img width="1919" height="1012" alt="image" src="https://github.com/user-attachments/assets/5d4c1156-86c7-4d9c-b029-946bbd5d6527" />

## XNOR of 16 bit numbers ALP

```
MOV BX,3527H
MOV CX,2968H
XOR BX,CX
NOT BX
RET
```

## OUTPUT

<img width="1919" height="1010" alt="image" src="https://github.com/user-attachments/assets/b5b44581-1c62-47b3-a743-43e80882dfb1" />

## NOT of 16 bit numbers ALP

```
MOV AX,276DH
NOT AX
RET
```

## OUTPUT

<img width="1919" height="1005" alt="Screenshot 2026-10-29 185042" src="https://github.com/user-attachments/assets/38fdfbfd-95f4-4b56-962f-40ddbc8ff8f4" />




## Result :
 
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.







