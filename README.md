# EXPERIMENT--01-ALP-FOR-8086
## Name : Subash E
## Roll no : 212223040209
## Date of experiment : 19-08-2025





## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AX, 4535H
MOV BX, 733FH   
ADD AX,BX
RET
```
## Output  

<img width="1852" height="1017" alt="image" src="https://github.com/user-attachments/assets/8fae155b-b60a-4ae4-974e-71d817d35b31" />

 
## Subtraction   of 8 bit numbers  ALP 
```
MOV AX, 4535H
MOV BX, 733FH   
SUB AX,BX
RET
 ```
## Output  
<img width="1876" height="1017" alt="image" src="https://github.com/user-attachments/assets/cb9d7ae4-ee98-4705-96bf-b5447bc431a5" />

## Multiplication alp 
```
MOV AX, 4535H
MOV BX, 733FH   
MUL AX
RET
```
 ## Output  
 <img width="1846" height="1027" alt="image" src="https://github.com/user-attachments/assets/7cf3f3ce-a5e6-4933-9679-40b485b10037" />



## Division alp 
```
MOV AX, 4535H
MOV BX, 733FH   
DIV AX
RET
```

## Output  
<img width="1888" height="1012" alt="image" src="https://github.com/user-attachments/assets/5e6d7374-e040-44f9-bc4e-57d70a2d0c0d" />

## Programs for Logical operations

## Logical bit numbers

```
org 100H
MOV AX, 4535H
MOV BX, 733FH   
AND AX,BX 
MOV [2000H],AX 


MOV AX, 4535H 
MOV BX, 733FH    
OR  AX,BX
MOV [2002H],AX 


MOV AX, 4535H 
MOV BX, 733FH    
XOR AX,BX
MOV [2004H],AX 


MOV AX, 4535H  
NOT AX
MOV [2006H],AX   


RET

```


## Output

<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/d7823390-b938-4009-ba6b-fabb7e697782" />



## Result :

 The execution of ALP on fundemental arithmetic and logical operations executed successfully.








