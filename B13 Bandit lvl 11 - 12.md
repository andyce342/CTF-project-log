Bandit lvl 11-12:

What it asking for: The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions. 

What I did/tried: ls and it show the text, read it there a text but I don't know and it over 13 letter. So I combined a previous command into cat command which read and reveal the new text; the password. 

(Command that worked:ls, cat data.txt | tr 'A-Za-z' 'NOPQRSTUVWXYZABCDEFGHIJKLMnopqrstuvwxyzabcdefghijklm') 
why I did: 
The file is being read and pipes into tr which translate the corresponded original letters into a new letter which in this case the new letter is 13 position after the original letter in alphabetical order; the number isn't being moved. 

(password:GROozWPO8QyN0mGrjUkID0WCYkZiQxrN) 
