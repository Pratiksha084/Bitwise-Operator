# Bitwise-Operator
In C++, bitwise operators perform operations on integer data at the individual bit-level. These operations include testing, setting, or shifting the actual bits. For example,

a & b; a | b;

Here is a list of 6 bitwise operators included in C++.

Operator Description & Bitwise AND Operator | Bitwise OR Operator ^ Bitwise XOR Operator ~ Bitwise Complement Operator << Bitwise Shift Left Operator

Bitwise Shift Right Operator

C++ Right Shift Operator

The right shift operator shifts all bits towards the right by a certain number of specified bits. It is denoted by >>.

When we shift any number to the right, the least significant bits are discarded, while the most significant bits are replaced by zeroes.

One bit Right Shift Operator

image

As we can see from the image above, we have a 4-bit number. When we perform a one-bit right shift operation on it, each individual bit is shifted to the right by 1 bit.

As a result, the right-most bit is discarded, while the left-most bit remains vacant. This vacancy is replaced by a 0.

C++ Left Shift Operator

The left shift operator shifts all bits towards the left by a certain number of specified bits. It is denoted by <<.

image

As we can see from the image above, we have a 4-bit number. When we perform a 1 bit left shift operation on it, each individual bit is shifted to the left by 1 bit.

As a result, the left-most bit is discarded, while the right-most bit remains vacant. This vacancy is replaced by a 0.
