# 6_loops_c++
# Aim
To understand and implement looping statements in C++:

for loop

while loop
## 📚 Theory:
Loops in C++ are used to execute a block of code repeatedly until a certain condition is met. The two primary loops discussed here are:

- **`for` loop**: Best when the number of iterations is known.
- **`while` loop**: Preferred when the number of iterations is uncertain and depends on runtime conditions.

###  Loop Syntax:

```cpp
// For loop
for(initialization; condition; increment/decrement) {
    // Code block
}

// While loop
while(condition) {
    // Code block
}```

## Differences between `for` and `while` Loops

| Aspect               | `for` Loop                                                                 | `while` Loop                                                                |
|----------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Use Case             | Best when the number of iterations is **known**                            | Preferred when the number of iterations is **unknown or condition-based**   |
| Initialization       | Done **within** the loop declaration                                       | Done **outside** the loop                                                   |
| Condition Checking   | At the **start** of each iteration                                          | At the **start** of each iteration                                          |
| Update Statement     | Defined **in the loop header**                                              | Has to be **manually handled inside** the loop body                         |
| Syntax Length        | **Compact** and easier to write for fixed loops                            | Slightly **longer** as update needs to be handled manually                  |
| Readability          | More readable for **count-controlled loops**                               | More readable for **event-controlled loops**                                |
| Infinite Loop Risk   | **Less likely** if properly written                                         | **Higher** if the update condition is missed                                |
| Example              | `for(int i=0; i<n; i++)`                                                    | `while(i<n)`                                                                |~```


## Important Theory Concepts:
#### Nested Loops:
Used for row and column control. Outer loop controls rows, inner loop controls columns/spaces.

ASCII Values for Characters:
Alphabets are printed using ASCII values:

'A' = 65

printf("%c", 65); prints A.

Spacing:
Spaces (" ") are important to align patterns correctly (especially for mirrored or centered shapes).

Pattern Formulae:
Stars in equilateral: 2i - 1 or 2i + 1

Mirroring: Print (n - i) spaces before printing stars/numbers
