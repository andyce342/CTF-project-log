Bandit lvl 13-14:
(Command that worked:ls, cat sshkey.private, touch bandit14.key, nano bandit14.key, ssh -i bandit14.key bandit14@bandit.labs.overthewire.org -p 2220, cat /etc/bandit_pass/bandit14)

What I did/why I did: 
This time you get a actual key that allows you to login to the next level where you open it and read the file that contain it. Unfortunately you can't directly use it in bandit directory to jump into another level therefore you need to create a file(touch) and store the actual textual information of the key in the file (nano;edit) where you use the key file (-i allows the terminal to verify you using the key file) to login to the user. Unfortunately whe we login to bandit14 we can't directly find the exact file(/etc = root server; files. While we are in /home = home directory therefore ls is out of lens to find the exact file) but we use given the file therefore we can just cat it. 

(password:aaWecNkG4FhxJQxz07uiwzVP6bJiYS65) 
