**This is a demo to github**<br/>

Step 1: **Looking up an account**<br/>
You need to look up your course specific account for CSE 15L:<br/>
Link to get there -> [Link](https://sdacs.ucsd.edu/~icc/index.php)<br/>
![Image](ss 2.png)<br/>

Change your password and wait for 15 minutes until you can use the password.

Step 2: **Installing VScode**

Install Visual studio code.

Link to get there -> [Link](https://code.visualstudio.com/)

Follow the instructions in the website on how to download vs code.

Step 3: **Remotely Connecting**

Open VScode and open the terminal. Type in *ssh cs15lfa22me@ieng6.ucsd.edu* where cs15lfa22me should be your account name. The two last letters should be different for each student so be careful when typing it.

![Image](ss 3.png)

Type yes, and enter your password. Once you are connected your terminal should look like this.

![Image](ss 4.png)

Step 4: **Trying Some Commands**

You are now connected remotely! Let's try some commands such as cd, ls, and pwd.

![Image](ss 5.png)

Step 5: **Moving files with scp**

Let's try to move files from your computer remotely! We will be using the scp command. We are trying to move a file called WhereAmI.java.
Compile WhereAmI.java in your computer and try to do it remotely!

Here's an example of it being compiled on my computer. 

![Image](ss 6.png)

Type in *scp WhereAmI.java cs15lfa22me@ieng6.ucsd.edu:~/* where cs15lfa22me should be your account name. If it runs correctly it should show this.

![Image](ss 7.png)

Log back in and try running the folder!

![Image](ss 8.png)

Notice that the output is different because its running in the remote computer.

Step 6: **Setting an SSH Key**

I'm stuck on this part. I'm running it on windows and there is an extra step that made me confused on what I should do.
![Image](ss 9.png)

In the image, I made the key but ssh-add should be the part where I get lost. **Note: I'll post the problem at piazza but I can't complete this part as it is 
                                                                                      10:45 PM now and fixing this will make my submission late.**

Step 7: **Optimizing Remote Running**

You can write a command in quotes at the end of an ssh command to directly run it on the remote server, then exit.

Example: *ssh cs15lfa22@ieng6.ucsd.edu "pwd"* will display the current directory on the remote computer.

Typing the up-arrow in your keyboard can recall your previous commands in the terminal.

