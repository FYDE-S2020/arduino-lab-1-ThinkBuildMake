Name: Michael Chuang

EID: mrc4375

Team Number: F1

## Questions

1. Why does your program need a setup and a loop?

    your answer here

2. What is the downside to putting all your code in a loop?

    It makes the code harder to read and debug, and it might be more inefficient if there are repeated steps.

3. Why does your code need to be compiled?

    The computer needs to be able to read the program, thus the compiler translates the code to machine code. The computer (or arduino in this case) can only read machine code.

4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

    When we lowered the frequency, I began to notice the flickers as it became dimmer. The issue is the fact that our eyes sample at a rate of ~30Hz. We'll notice flickering anything less than that frequency. One solution is to increase the frequency above the threshold the eye can see. Another solution is to just vary the voltage instead of sending waves (although this will drain battery much faster and the device may not like the lower voltage).

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    Ground is what the arduino and logic analyzer use as a reference. Thus, in order to measure the same voltage/output the same voltage, the devices must be using the same reference.

6. What is the difference between synchronous and asynchronous communication?

    your answer here

7. Profile of UART: Sent X bytes in Y time 

    your answer here

8. Profile of SPI: Sent X bytes in Y time

    your answer here

9. Why is SPI so much faster than UART?

    your answer here

10. list one pro and one con of UART

    your answer here

11. list one pro and one con of SPI

    your answer here

12. list one pro and one con of I2C

    your answer here

13. Why does I2C need external resistors to work?

    your answer here

## Screenshots

Procedure A, step 1:
![Put path to your image here ->](img/SaleaeScr.png)

Procedure A, step 4:
![Put path to your image here ->](img/Dimmer.png)

Procedure B, UART:
![Put path to your image here ->](img/placeholder.png)

Procedure B, SPI:
![Put path to your image here ->](img/placeholder.png)
