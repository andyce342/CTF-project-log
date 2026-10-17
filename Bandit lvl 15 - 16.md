Bandit lvl 15-16:

What it asking for: The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL/TLS encryption. Helpful note: Getting “DONE”, “RENEGOTIATING” or “KEYUPDATE”? Read the “CONNECTED COMMANDS” section in the manpage.

(Command that worked:openssl s_client -connect localhost:30001,pbLYuZtTg4MgaqfJx8jbA9gKKGqM68A7)

What I did/why I did: 
So basically openssl receive a cerification to verified the server identity (handshake) and s_client allows the connect server and port to transfer the message in a encrypted way to ensure privacy.

(password:kS0Hf0u5HiXFwKMKFqXvPdOTNGGa0X8V) 
