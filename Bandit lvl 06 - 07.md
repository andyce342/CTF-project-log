Bandit lvl 6-7:

What it asking for: The password for the next level is stored somewhere on the server and has all of the following properties: owned by user bandit7, owned by group bandit6 and 33 bytes in size

(Command that worked:find / -user bandit7 -group bandit6 -size 33c, cat /var/lib/dpkg/info/bandit7.password)

What I did/why I did: 
This time we going to find password somewhere in the server that fit specific characteristic; / is root directory meaning search in the entire server for this [something]. 
cat read that specific finding. 

(password:Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3) 
