# Storing Hex Value in the Memory.
This program loads A and adds B, which will then store in C.
| Position | Memory | Instruction |
|--------|--------|--------|
| 000 |  | Load A |
| 001 |  | Add B |
| 010 |  | Store C |
| 011 |  | 00000 |
| 100 | A | 00111 |
| 101 | B | 00110 |
| 110 | C | 00000 |
| 111 | D | 00000 |

### Load A
![load1](https://github.com/user-attachments/assets/0a5e94e5-72d1-4ef9-9f90-9d3333899a84)

### Add B
![andC](https://github.com/user-attachments/assets/9ef0f766-d3e9-4fd9-a471-ce3b32766af8)

### Store C
![storeC](https://github.com/user-attachments/assets/b2a7ea3d-9f6e-4b0c-b536-2daeae553427)

### Updated Memory
| Position | Memory | Instruction |
|--------|--------|--------|
| 000 |  | Load A |
| 001 |  | Add B |
| 010 |  | Store C |
| 011 |  | 00000 |
| 100 | A | 00111 |
| 101 | B | 00110 |
| 110 | C | 01101 |
| 111 | D | 00000 |

### New Instructions
This program loads A and ands B, which will then store in D.
| Position | Memory | Instruction |
|--------|--------|--------|
| 000 |  | Load A |
| 001 |  | And B |
| 010 |  | Store D |
| 011 |  | 00000 |
| 100 | A | 00111 |
| 101 | B | 00110 |
| 110 | C | 01101 |
| 111 | D | 00000 |

### Load A
![load1](https://github.com/user-attachments/assets/0a5e94e5-72d1-4ef9-9f90-9d3333899a84)

### And B
![and](https://github.com/user-attachments/assets/e603acbb-2c7c-40a0-981c-661245a97212)
### Store D
![storeD](https://github.com/user-attachments/assets/07756b4b-6379-4dd2-b883-dd19bff462c1)
### Updated Table
| Position | Memory | Instruction |
|--------|--------|--------|
| 000 |  | Load A |
| 001 |  | And B |
| 010 |  | Store D |
| 011 |  | 00000 |
| 100 | A | 00111 |
| 101 | B | 00110 |
| 110 | C | 01101 |
| 111 | D | 00110 |
