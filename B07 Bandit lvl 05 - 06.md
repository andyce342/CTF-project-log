Bandit lvl 5 - 6:

What it asking for: The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties: human-readable, 1033 bytes in size and not executable. 

What I did/tried: When in the inhere inventory and discover that there is a bunch of the files therefore I tried to the use file command which did nothing because it display directory on all of them. Given that in the bandit level description command list and the instructions I used the find command and mess around bit and find the right one. 

(Command that worked:ls, cd inhere, ls, find . -size 1033c ! -executable, cd maybehere07, ls -la, cat .file2).     
why I did: ls display what in the directory and inhere is a folder rather a file therefore cd allows you to enter into that folder which you use ls to see folders or ls -a to be sure.
Because there's many folders in the inhere the find command allows us to find the folder with the right properties (1033 bytes, not executable).
cd move into the fold and ls -la (-l) is the long list format which displays permissions, owners, and exact file size in bytes and cat reads the file. 

(password: pXa26xhMWaC2SvDotA4r9EgZkulOeSBW) 
