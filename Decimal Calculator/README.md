![lab11](https://user-images.githubusercontent.com/55320801/208474684-1f8db4f8-a110-4c7f-94aa-5ba9a98ceac6.gif)


This will be a two-part design lab, in which you will implement a hexadecimal calculator for the first part, and modify it to build a BCD calculator for the second one. A hexadecimal calculator (within the scope of ECE 270) is a device that can add and subtract two numbers (which can be of the form 0-F) resulting in a number that can also be displayed in hex. A BCD calculator, on the other hand, functions like a regular calculator in that it will make calculations only using the digits 0-9.

Since you've gotten the nitty-gritty of number entry out of the way in the first half of this design lab, you will now focus entirely on the BCD arithmetic (since no one calculates in hex), with which you will change the hex calculator you designed to calculate to count in decimal, so instead of going through 8,9,A,B,C, it would go through 8,9,10,11,12. In addition, you'll clean up the design so it doesn't show all the digits at once and that it doesn't accept keys A through F.

