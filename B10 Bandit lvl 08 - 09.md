Bandit lvl 8-9:

What it asking for: The password for the next level is stored in the file data.txt and is the only line of text that occurs only once. 

What I did/tried: ls the directory and again there the data.txt file. Two of the command example for the bandit pipe command guide match the description of the level, the usage of the command match (I think?), so I combine a specific part of the two command example into a new one and it worked! 

(Command that worked:ls, sort data.txt | uniq -u)
why I did: ls display the data.txt and because the password in siting in a bunch of identical words sort allows the words to be in alphabetical order which allows uniq -u to idenity which ones are duplicates and spit only the ones that doesn't repeats. Also |(pipe function) allow one function outputs to serve as an input to another function left -> right order. 

(password:EjmOSvuAu7sGAHqHVcBDPirRe9T03kxl) 
