General skill - strings it

What it asking for: Can you find the flag in file without running it? It asking if you use the strings command to access the flag. 

What I tried: Tried to the use the cat the file but it display a bunch random texts. Used the strings(which print the strings/lines of printable characters in files) command like suggested in the hints and since we know that whatever the flag is it has to include academy therefore we can pipe the output of the string command into the grep to find the which line include the keyword academy. 

What worked: (Command:wget [url], strings {file_name} | grep academy)


