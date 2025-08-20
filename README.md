# EXPERIMENT--01-ALP-FOR-8086
Name :DHARSHINI S
Roll no :212224100012 
Date of experiment :20-08-2025





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
mov al,53h
mov bl,24h
add al,bl
hlt
```

## Output  
<img width="1248" height="1092" alt="Screenshot 2025-08-20 103647" src="https://github.com/user-attachments/assets/3a98c344-cd9b-472c-91aa-292573f8591f" />
 
## Subtraction   of 8 bit numbers  ALP 
```
mov ax,0402h
mov bx,0101h
sub ax,bx
hlt
```
## Output 
<img width="1243" height="1120" alt="image" src="https://github.com/user-attachments/assets/43ea49fe-f0a8-47a7-93ba-677db397f101" />

## Multiplication alp
```
mov ax,0402h
mov bx,0101h
mul bx
hlt
```
 ## Output  
 <img width="1213" height="1118" alt="image" src="https://github.com/user-attachments/assets/b8dec17f-742b-44bb-a38c-6e55d1385d39" />

## Division alp 
```
mov ax,53h
mov bx,24h
div bx
hlt
```
## Output 
<img width="1176" height="1088" alt="image" src="https://github.com/user-attachments/assets/432088d8-e21f-4cf6-b10c-7c2008f4c866" />

## AND alp 
```
mov al,53h
mov bl,24h
and al,bl
hlt
```
## OUTPUT:

<img width="1163" height="1111" alt="image" src="https://github.com/user-attachments/assets/7afb45c1-1322-4536-b669-e000accc48ff" />

## OR alp
```
mov ax,50h
mov bx,12h
or ax,bx
hlt
```
## Output:
<img width="1183" height="1109" alt="image" src="https://github.com/user-attachments/assets/62395167-2db4-4335-94c0-acb3df3ab494" />

## NOT alp
```
mov ax,50h
not ax
hlt
```
## Output:
<img width="1280" height="1108" alt="image" src="https://github.com/user-attachments/assets/f9ef950f-67dc-4e1a-94a9-3eb014eeb9b0" />

## XOR alp
```
mov ax,50h
mov bx,23h
xor ax,bx
hlt
```
## Output:
<img width="1209" height="1092" alt="image" src="https://github.com/user-attachments/assets/9e77eeb7-70ba-4cea-858c-55b173cbab65" />

## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.
 








