Bandit lvl 13-14:

What it asking for: The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Look at the commands that logged you into previous bandit levels, and find out how to use the key for this level. If you need help with this level: a hint file can be found in the home directory. Make sure to read the error messages as they are informative.


(Command that worked:ls, cat sshkey.private, touch bandit14.key, nano bandit14.key, ssh -i bandit14.key bandit14@bandit.labs.overthewire.org -p 2220, cat /etc/bandit_pass/bandit14)

What I did/why I did: 
This time you get a actual key that allows you to login to the next level where you open it and read the file that contain it. Unfortunately you can't directly use it in bandit directory to jump into another level therefore you need to create a file(touch) and store the actual textual information of the key in the file (nano;edit) where you use the key file (-i allows the terminal to verify you using the key file) to login to the user. Unfortunately whe we login to bandit14 we can't directly find the exact file(/etc = root server; files. While we are in /home = home directory therefore ls is out of lens to find the exact file) but we use given the file therefore we can just cat it. 

(password:aaWecNkG4FhxJQxz07uiwzVP6bJiYS65) 
