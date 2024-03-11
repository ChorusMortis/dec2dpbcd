# dec2dpbcd

A script that converts decimal values to densely packed BCD. For now, it uses string manipulation for the conversion algorithm.

It supports whitespaces and any number of decimal values in the input by:

1. Appending 0s in front of the decimal value if the number of digits is not divisible by 3
2. Splitting the decimal digits into groups of 3 starting from the least significant (rightmost) digit
