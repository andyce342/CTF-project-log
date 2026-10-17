Web Exploitation - where are the robots

What it asking for: Can you find the robots? http://chatelaine.cylabacademy.net:11372; Trying to find a special file within the website and find the flag. 

What I tried: Open up the website and trying to find any button that reveal anything helpful; right clicked a bunch of time(didn't do anything). Run the file in the terminal using wget, curl(command-line tool used to transfer data to or from a network server; web brower) and cat. 

What worked: (Command:{website}/robots.txt, {website}/91ac7.html(the forbidden file url/name))         
Adding the robots.txt allow the user to see what file isn't accessible to the user which in this case there's only one. Add the file to the url and it will redirect you to the website that display the flag. 

Ai log: Explained what I tried and the ai explain that there's a concept called robot.txt and hinted that maybe this has something to do with the challenge. It tried that method for five time and the ai started to redirect to solve the problem by using inspect function in the web browser; spent about 20 mins talking about how to enable the developer mode. I finish doing that and decided to the figure out myself which apparently to be the problem of a typo. 
