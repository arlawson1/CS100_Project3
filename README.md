# CS100_Project3
A cpp program to count the number of keystrokes by each finger

This program takes a hard-coded approach to count the number of key presses each finger makes given a typed block
 of characters input by the user (using ascii codes).
 
This is accomplished by brute force, increasing two of twelve integers (one for each finger, one for each hand) for each character
(by 1, or 2 if a capital letter or Shift-symbol) in a given block of text.

The program then outputs the count of strings input, the total characters counted, the total strings typed using only one hand,
 the total keystrokes, and the keystrokes by each finger.
