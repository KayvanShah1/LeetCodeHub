#### Description:
1. Essentially, what we asked to do here is to convert a number in the base 26 numeral system to a decimal number.
1. This is a standard algorithm, where we iterate over the digits from right to left and multiply them by the base to the power of the position of the digit.
1. To translate a letter to a number we use the Python method ord which returns the Unicode code of the letter.
1. By subtracting the code by 64, we can map letters to the numbers from 1 to 26.
​
​