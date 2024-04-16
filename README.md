### Name : MAMTHA I

### Roll no : 212222230076

# EXPERIMENT 01- ARITHMETIC OPERATION AND LOGICAL OPERATION IN 8086






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
5.	 
6.	Run (once there is no syntax error) 

7.	Click OK to see/view the output of your program on the Emulator screen. 


8.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
9.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)



9.	Click on emulate to start emulation 


![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)


10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 


![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations :

### Addition  of 8 bit ALP  :
```
mov ax,0b2h;
mov bx,0c3h;
add ax,bx;
mov [2345h],ax;
ret
```




### Output  :
![Screenshot 2024-02-20 160244](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/165ad1ca-936c-4255-b5d2-7d40d12cd37f)

 
### Subtraction   of 8 bit numbers  ALP :
```
mov ax,04f3h;
mov bx,05c3h;
sub ax,bx;
mov [2345h],ax;
ret

```
 
### Output  :
![Screenshot 2024-02-20 160634](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/5ec8b4ce-87e5-461c-b1a8-d7b7ecdbe8f3)

### Multiplication alp :
```
mov al,03h;
mov bl,02h;
mul bl;
mov [2345H],al;
ret
```



 ### Output  :


![image](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/97403c22-9767-41b8-91bb-ae5b1f240c9a)



### Division alp :
```
mov al,08h;
mov bl,02h;
div bl;
mov [2345H],al;
ret 
```


### Output  :

![image](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/0024b9ff-5e0f-49f7-9ebd-2691c0a38c1f)

## Programs for logical  operations

## AND
```python
org 100h
mov bx,1000h;
and bx,1111h;
mov [0040h+02],bx;
ret
```
## Output 
![image](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/a4eff926-39a2-438a-bf14-05110e2ee24b)

## OR
```python
org 100h
mov ax,[0040h+06];
mov bx,1000h;
or ax,bx;
mov [0040h+02],ax;
ret
```
## Output
![image](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/1d4d983f-ec0a-4f8b-a7a3-2a5657c37784)

## NOT
```python
org 100h
mov bx,0040h;
mov ax,[bx]; 
not al;
mov [0040h+04],ax;
ret
```
## Output
![image](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/203ad53e-5d22-4fd9-b067-ff7ab8af6ebc)

## XOR
```python
org 100h
mov bx,0040h;
mov ax,[bx]; 
xor ax,bx;
mov [0040h+04],ax;
ret
```
## Output:
![image](https://github.com/Mamthaiyappaprabu/EXPERIMENT--01-ALP-FOR-8086/assets/119393563/5e5d89c7-e3bf-423e-9f42-a91c520378e7)




## Result :
Thus, A Program Is Develope To Write And Execute ALP On Fundamental Arithmetic And Logical Operations.
 








