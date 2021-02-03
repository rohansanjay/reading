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