Bandit lvl 9-10:

What it asking for: The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

What I did/tried: ls, search the command in the command you might need list from the level description (only two I didn't know since most of it was covered in the previous levels or guide thing, one of which was string), and I combined the two command that I think was the right one but it wasn't; replace the wrong one with string and it worked. 

(Command that worked:ls, strings data.txt | grep =)   
why I did: 
ls find what in the directory and because we are trying to find the password inbetween human readable characters and = signs; the string command find the line with those character and pipes into grep to clear the lines that doesn't have equal signs. 

(password:B0s2khmbT9u0geKuOoVGW3JZKhndE3BG) 
