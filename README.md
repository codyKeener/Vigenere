# Vigenere
CS50 Vigenere

HarvardX CS50 Problem Set 2 - Vigenere

https://docs.cs50.net/2018/x/psets/2/vigenere/vigenere.html

My code compiles and outputs ciphertext, but not the correct ciphertext.  From debugging, I found that int J continues to increase, when it should "wrap around" and reset to 0 after it gets to the same number as the length of the key.  I think I have to put in some code like 'J % strlen(keyword)' or something like that, but I don't know where to put it or if it needs to be in a for loop or something else.  Halp plz!
