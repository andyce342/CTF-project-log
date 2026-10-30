Cryptography - Mod 26

What it asking for: Cryptography can be easy, do you know what ROT13 is? values.txt. It just asking if you can decode the message in the text file using the ROT13 (a method that replaces each alphabet letter with the letter 13 positions after it alphabetical order) 

What I tried: Searched how the ROT13 encryption works and find out its the exact same as the one in Bandit 11 - 12 lvl; copy and pasted the command to solve.  

What worked: (Command:wget [url], cat {file_name} | tr 'A-Za-z' 'NOPQRSTUVWXYZABCDEFGHIJKLMnopqrstuvwxyzabcdefghijklm')          
You get the file and cat it to read it which is piped in to the tr which translate each letter to the it new (correspond) letter to decode it. 
 
