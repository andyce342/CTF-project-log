Bandit lvl 0-1:

What it asking for: The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game. 

What I did/tried: Searched the different command that list in the may used section of the level introductions and tested them out. 

(Command that worked: ls, cat readme, exit, ssh bandit1@bandit.labs.overthewire.org -p 2220)  
why I did: 
ls is the display button that shows what in the directory/inventory of the current server. 
cat is basically the read or display what in the given file which in this case is readme. exit is basically you leaving the server. 
ssh bandit@bandit.labs.overthewire.org -p 2220 is login into level 1.

(password:6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR) 
