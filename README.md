Half-Adder Portfolio Page

Purpose

This repository serves as a demonstration of my understanding of binary addition and its practical applications. In this project, I explain one of the simplest methods for adding two binary numbers: the half adder. A half adder is a fundamental digital circuit that computes the sum and carry of two single-bit binary numbers. It serves as the foundation for more complex circuits, such as full adders and multi-bit adders like the 4-bit adder.

Understanding Binary Addition

Binary numbers consist of only 0s and 1s, unlike the decimal system, which uses digits from 0 to 9. Due to this, binary numbers tend to appear longer as they increase in value. For instance, the decimal numbers 0 through 5 are represented in binary as follows:
![image](https://github.com/user-attachments/assets/93d3b172-31db-4c09-b26d-acdad6d0299a)

Explanation:

When both inputs (A and B) are 0, the sum (S) is 0, and the carry-out (Cout) is 0.

When A is 0 and B is 1 (or vice versa), the sum (S) is 1, with no carry (Cout = 0).

When both inputs are 1, the sum (S) is 0, but the carry-out (Cout) is 1 because 1 + 1 equals 10 in binary, where 0 is the sum and 1 is carried to the next column.

Logical Gates Used

A half adder is built using two fundamental logic gates:

XOR Gate: Produces the sum (S = A ⊕ B)

AND Gate: Determines the carry (Cout = A • B)

Half Adder Circuit Diagram



In this circuit, the XOR gate computes the sum, while the AND gate calculates the carry bit.

Implementing the Half Adder

Using an integrated circuit (IC), I constructed a simple half adder. The images below illustrate the functionality of the circuit:

Both inputs are 0

Result: Both the Sum (S) and Carry-out (Cout) LEDs remain off.



Inputs: A = 0, B = 1

Result: The Sum (S) LED lights up, while Cout remains off.



Inputs: A = 1, B = 1

Result: The Sum (S) LED turns off, while the Carry-out (Cout) LED turns on.



This behavior mimics decimal carrying, where adding numbers past a base threshold (e.g., 9+1 in base 10) results in a new column.

Extending to Multi-Bit Addition

While a half adder is useful for single-bit operations, adding multiple bits requires a full adder, which consists of two half adders and an OR gate. The full adder accounts for an additional input, Cin (carry-in), ensuring proper multi-bit addition across multiple places.

This project provides a foundational understanding of binary addition and digital logic circuits. Moving forward, I aim to explore full adders, multi-bit binary arithmetic, and their real-world applications in computational hardware.
