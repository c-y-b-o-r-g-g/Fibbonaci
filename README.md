# Fibbonaci
 
# Fibbonaci.py

This Python script contains a function `fibbonaci(end)` that generates the Fibonacci sequence up to a specified number.

## Function Details

### `fibbonaci(end)`

This function generates and prints the Fibonacci sequence up to the number specified by the `end` parameter.

#### Parameters:

- `end`: A number that specifies the upper limit for the Fibonacci sequence. The function will generate numbers in the Fibonacci sequence that are less than or equal to this number.

#### Behavior:

The function initializes two variables, `a` and `b`, to `0` and `1` respectively. These represent the current and next numbers in the Fibonacci sequence.

It then enters a loop that continues until the current number `a` is greater than or equal to `end`.

Inside the loop, it first prints the current number `a`, followed by a space. It then updates `a` and `b` to `b` and `a + b` respectively, which are the next two numbers in the Fibonacci sequence.

After the loop ends, it prints a newline to finish the sequence.

## Usage

At the end of the script, the `fibbonaci` function is called with `end` set to `2500.1`. This means that when the script is run, it will print the Fibonacci sequence up to `2500.1`.

To use the function with a different `end` value, you can modify this line of code, or call the `fibbonaci` function elsewhere in your code.
