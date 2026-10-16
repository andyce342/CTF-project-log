General skil - Obedient Cat

What it asking for: 
It started that "This file has a flag in plain sight (aka "in-the-clear"). flag" which simply means open and read the file to obtain the flag.

What I tried: 
I first opened the file that linked on the word file which got downloaded and display a plain text (it didn't seem like the flag to me during the time since the input section has 3 dots which indicated that the flag should be 3 letters) and I ignore it. Since it stated that file needed to be open to access for the flag, I used ls/ls -a to display the files in the directory and there's a file called README.txt. I cat the file and it doesn't contain the flag, provide basic guidance and also tips (didn't read it carefully). I opened the hints (didn't read carefully again) and saw two commands wget and man cat, entered both commands one doesn't work due to format error and another is the guide/menual to the cat command.     

What worked: (Command: wget [url], ls(optional), cat [the filename that obtain from the wget]) 
 Simplest and shortcut way: Just click on the link on the word flag it will download the file and it will display the flag. 
 The proper way: copy the link and use wget (World Wide Web get, it is used download files directly from the internet) to obtain the file and cat it. 

The AI log: 
Asked assistant what I did and what does the hint mean in the challenge. It kept hinting that maybe there is something in the link that might help complete the level. I told it that it was just a piece of the text and it hinted that it might the key to success(flag) which I kept saying it not until I actually submit it trying to prove it wrong; it turn it was the flag. It also direct me to the wget method where it direct me to an format of how the wget is supposed to be used but it also advice me to use man cat to read the file because it was listed on the hint section. I ignored that part because I had tested before already and just read the file using the normal cat. 
