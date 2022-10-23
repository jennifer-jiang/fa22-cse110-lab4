1. The bug was that the numbers, num1 and num2, were treated as strings. Therefore, when num1 and num2 were added in calculateSum(), they were concatenated instead of added numerically.
2. To fix it, I would use Number() to convert the strings to numbers.
