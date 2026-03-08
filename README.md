# Transistor-Based-Constant-Current-Source-for-Driving-Parallel-LED-Arrays
Transistor-Based Constant Current Source for Driving Parallel LED Arrays

This project demonstrates the design and simulation of a constant current source using bipolar junction transistors (BJTs) to drive multiple LEDs with stable current.

The circuit uses two transistors:

Q1 (2N5401) acts as the current control transistor that regulates the current flowing through the LED array.
Q2 is used to create a stable reference voltage for the base of Q1.

Operation
A voltage divider network composed of R4, R3, and R1 establishes a reference voltage that biases transistor Q2.
Q2 operates as a voltage stabilizer (emitter follower). Its purpose is to maintain a stable base voltage for Q1, preventing variations caused by load changes or transistor gain differences.
Because the base voltage of Q1 remains nearly constant, the voltage across resistor R2 (220 Ω) also remains nearly constant.

<img width="942" height="1272" alt="image" src="https://github.com/user-attachments/assets/c9c7dec2-5c15-4ed5-bc91-e50343548dab" />

<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/8a2dc0f8-e0d9-4b70-87f2-0e62f7540c56" />
<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/eefb5a7c-20cb-4640-a1e7-ae0ddf02d0a9" />
