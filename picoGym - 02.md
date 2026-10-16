General skills - Wave a flag

What it asking for: Can you invoke help flags for a tool or binary? This program has extraordinarily helpful information. Basically it is asking if you can run a program help option. 


What I tried: Used wget command and looked at the hints for a better understanding of what the challenge is asking for. I changed the permission according to the challenge so it allows the user(me) to execute command upon the file. Tried to used the ./ command by itself even though it was an aid function and -h command shown in the hints; none of them worked 

What worked: (Command:wget [url], chmod +x warm, ./{file_name} -h(--help))                    
Combined ./ and -h command to get it display the flag; the ./ specify which file to execute and -h is the help function which can be customized to display anything (in this case it the flag). (Or you could literally cat it and look through the file until you find a section that contain a message and the flag) 

The AI log: Asked what is the -h command line is and specifically why it doesn't print instruction or tips like I had expected in the help function. It explain that -h doesn't really mean anything it just internal function that display helpful text(usually instructions) from the creator to the user; meaning the text in -h can be anything. 
