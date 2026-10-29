Web Exploitation - where are the robots

What it asking for: Can you find the robots? http://chatelaine.cylabacademy.net:11372; Trying to find a special file within the website and find the flag. 

What I tried: Open up the website and trying to find any button that reveal anything helpful; right clicked a bunch of time(didn't do anything). Run the file in the terminal using wget, curl(command-line tool used to transfer data to or from a network server; web brower) and cat. 

What worked: (Command:{website}/robots.txt, {website}/91ac7.html(the forbidden file url/name))         
Adding the robots.txt allow the user to see what file isn't accessible to the user which in this case there's only one. Add the file to the url and it will redirect you to the website that display the flag. 

