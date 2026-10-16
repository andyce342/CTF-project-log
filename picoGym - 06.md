Forensics - Glory of the Garden

What it asking for: This file contains more than it seems. Get the flag from garden.jpg; Read the file  to find the flag.

What I tried: Obtain the file wget and run it using cat where I discovered that at the very last line of the file information it stated "Here is the flag:". 

What worked: (Command:wget{file}, strings {file} | grep academy)          
Since I saw that there literally text string allows to filter those printable texts, which included the flags, and pipe it into grep to filter for academy for the flag. 
