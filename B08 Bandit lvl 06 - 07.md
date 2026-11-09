Bandit lvl 6-7:

What it asking for: The password for the next level is stored somewhere on the server and has all of the following properties: owned by user bandit7, owned by group bandit6 and 33 bytes in size

What I did/tried: I used the standard ls command but this time it doesn't show anything. Use the previous format of find command thinking that it will work but it didn't therefore I went a deeper digging for the find command and find that you need to find the special command in order to search in the root directory itself. 

(Command that worked:find / -user bandit7 -group bandit6 -size 33c (or add: 2>/dev/null), cat /var/lib/dpkg/info/bandit7.password)
why I did: 
This time we going to find password somewhere in the server that fit specific characteristic; / is root directory meaning search in the entire server for this [something].(2>/dev/null means that anything that permission denied(number 2 and 1 is permission allowed) is thrown away and will not be displayed. cat read that specific finding. 

(password:Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3) 
