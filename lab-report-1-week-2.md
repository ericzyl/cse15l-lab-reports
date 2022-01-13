# Lab 1: Remote Access to ieng6

## Task 1: Install VSCode

Go to Visual Studio Code [website](https://code.visualstudio.com/) to download it.

>Visual Studio Code combines the simplicity of a source code editor with powerful developer tooling, like IntelliSense code completion and debugging.

It also has a good user interface that allows us to interact with the terminal easily.
<br/>Once you set it up, you will see a page like below.

![image0](vscodepic.png)
<br/><br/>


## Task 2: Remote Connect
Open the terminal and enter assigned account and password just like below.
<br/>ssh cs15lwi22aft@ieng.ucsd.edu
<br/>And then you will see this picture.

![image1](image24.png)
I can see a Cluster status table. There are 5 columns within it: Hostname, Time, #users, load, and Averages.It also shows the date of last login. Username: cs15lwi22aft. Currently using 0% CPU on that server.
<br/><br/>


## Task 3: Try Some Commands
Here are some basic commands that I tried during my lab time.
* "cd" means change directory. 
<br/>"cd\" let you go back to root directory. 
<br/>"cd.." enables you to go back to previous directory

* "ls" means list.
<br/> "ls -a" shows all files. We can see the hidden files like some configurations. We can see files with different colors. Blue means folders. The green are those you are able to run.

* "man ls" to see manual of ls.
* "pwd" to print work directory
* "mkdir" to make new directory
* "scp" allows you to move your files
* Compile java file and run it: "javac" + filename to compile; "java" + filename to run it
* "cat" means concatenation. 
<br>cat > one text.txt
<br/>(enter your text here)
<br/>Ctrl D to go back
<br/>cat + onetxt.txt to view; or we can use more command: more onetext.txt


Picture of my trials.
![image2](lab1trialpic.png)
<br/><br/>


## Task 4: Use scp to Move Files
I firstly create a java file named "WhereAmI" at disk E folder CSE15L. This code would allow you to print the current directory. In the terminal, I type "scp" + file name + my username + :~/ to upload such file to my root folder in the server. From the picture in Task 3, you can see such file exists.
![image3](image2.png)

We can actually complie it and run it with "javac" and "java" commands. And it prints the directory indicating my location in the server.

![image4](whereAmIpic.png)
<br/><br/>


## Task 5: Setting an SSH Key



