# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END

```

## OUTPUT
<img width="1919" height="1199" alt="Screenshot 2026-02-11 103933" src="https://github.com/user-attachments/assets/c187b10c-496c-4c8d-81da-a3077ddda819" />

![WhatsApp Image 2026-02-21 at 8 34 58 AM](https://github.com/user-attachments/assets/79eb9740-5598-4904-ad63-941ca935fb8e)



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A,P0
MOV B, A
MUL AB
MOV R0,A
MOV A,R0
MOV B,P0
MUL AB
MOV P2,A
END

```


## OUTPUT
<img width="1919" height="1199" alt="Screenshot 2026-02-11 110632" src="https://github.com/user-attachments/assets/77d192be-ce27-4114-b3ce-4430dfaf0f5a" />

![WhatsApp Image 2026-02-21 at 8 35 20 AM](https://github.com/user-attachments/assets/4fa65f75-d175-4d36-89fb-024df29479e4)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


