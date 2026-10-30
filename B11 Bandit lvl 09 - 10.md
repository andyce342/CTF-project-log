Bandit lvl 9-10:

What it asking for: The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

(Command that worked:ls, strings data.txt | grep =)

What I did/why I did: 
ls find what in the directory and because we are trying to find the password inbetween human readable characters and = signs; the string command find the line with those character and pipes into grep to clear the lines that doesn't have equal signs. 

(password:B0s2khmbT9u0geKuOoVGW3JZKhndE3BG) 
