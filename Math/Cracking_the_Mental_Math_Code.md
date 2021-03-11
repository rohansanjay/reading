# Cracking the Mental Math Code by Yash Chandak

### 1.1 Fast Addition and Subtraction

- Add two digits at a time, write the answer for that, and maintain the carries
  - Ex: 1357 + 2633
    - 57 + 33 = 90
    - 12 + 26 = 39
    - Final answer: 3990
  - Ex: 2035 - 328
    - 35 - 28 = 7
    - 20 - 3 = 17
    - Final answer: 1707
- Note: subtract before you add because it's easier to deal with smaller numbers

### 1.2 PEMDAS Approximations

- Do operations for the highest 2 place values and round the rest because you estimate within 5%
  - Ex: 71239 + 47458 - 22334 
    - 71 + 47 - 22 = 71 + 25 = 96 -> 96000

### 1.3 Multiply by 11 and like

- Ex: 35 * 11
  - = 3 | 3 + 5 | 5 = 385
- Ex: 57 * 11
  - 5 | 5 + 7 | 7 = 627
- Process
  - Step 1: write 1s digit as 1s digit of answer
  - Step 2: add 1s digit to 10s -> if greater than 10, keep tens digit and carry the one
  - Step 3: write 10s digit as hundreds digit of answer (with carries)
- 3 digit example: 429 * 11
  - 4 |4 + 2 | 2 + 9 | 9 = 4719
- For 111, follow same steps as 11 but build to adding 3 digits at a time
  - Ex: 429 * 111
    - 4 | 4 + 2 | **4 + 2 + 9** | 2 + 9 | 9 = 475619
    - Rule: # of 1s = # of digits you have to add

### 1.4 Multiplying by 25

- Ex:
  - 56 * 25
    - = 56 * 25 * 4/4 = 56/4 * 25 * 4 = 56/4 * 100 = 1400
  - 47 * 25 
    - = 47/4 * 25 * 4 = 11.75 * 100 = 1175

### 1.5 Multiplying by 125

- 125 * 8 = 1000
  - Divide the number by 8 and multiply by 1000
  - Ex: 72 * 125 = 72/8 * 1000 = 9000

### 1.6 Multiplying by any Number Ending in 5

- Double the number ending in 5 and half the other one
  - Ex: 32 * 15 -> 32 / 2 * 15 * 2 = 16 * 30 = 480
  - Note: only do this if the other number is even

### 1.10 Multiplying 2 Numbers with an Even Difference

- a<sup>2</sup> - b<sup>2</sup> = (a + b)(a - b)
  - 22 * 24 = (23 - 1)(23 + 1) = 23<sup>2</sup> - 1<sup>1</sup> = 529 - 1 = 528
- Ex: 29 * 35 = (32 - 3)(32 + 3) = ...

### 1.11 Multiplying 2 Numbers with the Same Tens Digit and Ones Digits that Add to 10

- Step 1: multiply ones digit of both together (make it take up two place values ex: 09, 16, 21...)
- Step 2: multiply the tens digit by one more than itself
- Ex: 23 * 27 = 2 * 3 | 3 * 7 = 621

### 1.12 FOIL

- Very important trick
- ab = 10a + b and cd = 10c + d
  - = (10a + b) * (10c + d)
  - = 100ac + 10ad + 10bc + bd
  - = 100(ac) + 10(ad + bc) + bd
- steps
  - 1: ones digit of answer = product of ones digits of both numbers multiplied
  - 2: tens digs of answer = sum of product of outer digits plus product of inner digits
  - 3: hundreds digit = product of the tens digit of the two numbers multiplied
- Ex: 28 * 52
  - 8 * 2 = 16; write 6 & carry 1
  - 2 * 2 = 4 & 8 * 5 = 40; 4 + 40 + 1 = 45; write 5 carry 4
  - 2 * 5 = 10; 10 + 4 = 14
  - Answer = 1456

