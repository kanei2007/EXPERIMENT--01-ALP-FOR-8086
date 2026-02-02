# EXPERIMENT--01-ALP-FOR-8086
## Name : KANEIMOZHI S
## Roll no :212224040147
## Date of experiment : 02-02-2026





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
org 100h

mov al,76h

mov bl,22h
add al,bl

hlt

ret



## Output  
<img width="1920" height="1080" alt="Screenshot 2026-02-02 232245" src="https://github.com/user-attachments/assets/3cc54ca7-a825-480c-bf55-159ff3e990e8" />

 
## Subtraction   of 8 bit numbers  ALP 
org 100h

mov al,89H

mov bl,35H
sub al,bl


ret
## Output  
<img width="1920" height="1080" alt="Screenshot 2026-02-02 232839" src="https://github.com/user-attachments/assets/f02800f0-3123-4d30-95e1-cd4deee3fb52" />

## Flag 
<img width="121" height="358" alt="image" src="https://github.com/user-attachments/assets/f1831740-5c37-4434-8941-967f65679aaa" />

## Multiplication alp 
org 100h

mov al,43H

mov bl,22H
mul bl


ret
 ## Output  
<img width="1920" height="1080" alt="Screenshot 2026-02-02 233114" src="https://github.com/user-attachments/assets/1427a78b-7e8b-4754-8484-9478ab4dcd9c" />


## Division alp 
org 100h

mov ax,78H
mov bx,4H
div bx


ret
## Output  
<img width="1920" height="1080" alt="Screenshot 2026-02-02 233415" src="https://github.com/user-attachments/assets/ce4fbcd5-29d2-49a9-9ee3-5fb8f9ffae3b" />


## AND for 8 bit alp:
org 100h

mov al,[1000h]

mov bl,[109H]
AND al,bl


ret

## Output:
<img width="1920" height="1080" alt="Screenshot 2026-02-02 234256" src="https://github.com/user-attachments/assets/9d76040c-c40f-4ba3-94aa-1b012cbfc082" />


## OR for 8 bit alp:

org 100h

mov al,[1000h]

mov bl,[109h]
OR al,bl


ret

## Output:
<img width="1920" height="1080" alt="Screenshot 2026-02-02 234459" src="https://github.com/user-attachments/assets/415a85a9-66cf-468b-a568-ab7929231a2a" />

## NOT for 8 bit alp:
org 100h

mov al,[1000h]
NOT al


ret
## Output:
<img width="1920" height="1080" alt="Screenshot 2026-02-02 234654" src="https://github.com/user-attachments/assets/50bf92fe-347f-446c-90b7-37308ae7a88b" />

## NAND for 8 bit alp:
org 100h

mov al,[1000h]
mov bl,[109h]
AND al,bl
NOT al

ret
## Output:
<img width="1920" height="1080" alt="Screenshot 2026-02-02 234829" src="https://github.com/user-attachments/assets/e5a4a651-4dc9-460b-8b53-09c0877fbb61" />

## NOR for 8 bit alp:
org 100h

mov al,[1000h]

mov bl,[109h]
OR al,bl
NOT al  

ret
## OUtput:
<img width="1920" height="1080" alt="Screenshot 2026-02-02 235046" src="https://github.com/user-attachments/assets/e99e0b8d-98a5-4be4-bf8e-3f606dd99986" />


## XOR for 8 bit alp:

org 100h

mov al,[1000h]

mov bl,[109h]
XOR al,bl

ret
## output:
<img width="1920" height="1080" alt="Screenshot 2026-02-02 235334" src="https://github.com/user-attachments/assets/ee5c0a4f-1fad-44a9-b9cb-3060ce9c2da2" />

## XNOR for 8 bit alp:
org 100h

mov al,[1100h]

mov bl,[1102h]
XOR al,bl
not al


ret

## Output:
<img width="1920" height="1080" alt="Screenshot 2026-02-02 235450" src="https://github.com/user-attachments/assets/4eea9d90-eeba-4e32-a4c4-4d1de4d6f650" />


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








