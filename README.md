# <p align ="center"> EXPERIMENT--01-ALP-FOR-8086 </p>
### Name : SUBRAMANIYA PILLAI B
### Reg no: 212221230109




## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
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
mov al,24h
mov bl,24h
add al,bl
hlt
```


## Output  
![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/25e89d4e-acc9-4d29-9f85-ab194b34c42c)


 
## Subtraction   of 8 bit numbers  ALP 
```
mov al,24h
mov bl,14h
sub al,bl
hlt
```

 
## Output  
![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/57a3fe61-b83c-4122-b1cd-ad3e29056655)

## Multiplication alp 
```
mov al,10h
mov bl,6h
mul bl
hlt
```
 ## Output  


![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/f448dabb-6e11-4c34-a37e-27eabd48190f)



## Division alp 
```
mov al,40h
mov bl,2h
div bl
hlt
```
## Output  

![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/ecfe8f32-3bcf-4ae9-9bf5-f26395e69f80)

## Programs for logical operations
## AND alp
```
MOV AL,66H;
MOV BL,77H;
AND AL,BL
HLT

ret
```
## Output 
![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/8e97766c-2db0-4a03-84a5-31132f348dda)

## OR alp
```
MOV AL,99H;
MOV BL,66H;
OR AL,BL
HLT

ret 
```
## Output
![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/a013031d-0168-4a25-97b2-57d7653cb696)

## XOR alp
```
MOV AL,85H;
MOV BL,45H;
XOR AL,BL
HLT

ret                                           

```
## Output
![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/3dc51991-816c-460b-bbc5-26d69a0ff749)

## NOT alp
```
MOV AL,38H
NOT AL
HLT

ret
```
## Output
![image](https://github.com/Subramaniya-pillai/EXPERIMENT--01-ALP-FOR-8086/assets/94166127/6961d609-e5c3-4164-8349-700a3dfdd1a0)

## Result :
 Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.








