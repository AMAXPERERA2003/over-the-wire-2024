# Over-the-wire-2024

Over the wire is a game that can be accessed through the site https://overthewire.org/wargames/ . The walkthrough that is being displayed is bandit which is provided as the first level for a cybersecurity student that can be easily accessed freely and go on level by level.

Bandit is given through a overthewire server;
####To access the bandit server they give you some rules how to access

But as a first year cybersecurity student it is difficult access the server for the first time, but it is easier if you continue trying.

<h1>You can do it</h1>

<h2>Level 0</h2>
- First go to the overthewire site and then go to the bandit server. There they give you the level 0 rules and guide of how to do it.

<h2>Let's take a look at that</h2>

![image](https://github.com/user-attachments/assets/b0addc9d-efda-44c0-9f31-2a03c2119fa4)

<ul><li>To access the bandit server, turn on the windows powershell or the terminal in kali linux and then type the command;</li></ul>

<pre><code>ssh bandit0@bandit.labs.overthewire.org -p 2220
</code></pre>

To access the first and foremost level of the game,once you press enter you will get into the first level but they ask for a password so for the password type,

<pre><code>bandit0</code></pre> as the password.

![image](https://github.com/user-attachments/assets/6e4c9c96-ce1a-4ca9-bdcf-22f28bfc0b86)

![image](https://github.com/user-attachments/assets/5d7fa3ca-d3d1-4670-b8c9-e020de04a50c)

- There is no clue given in the code here so first check the file directory by typing, 
<pre><code>ls</code></pre>
Then you get a file/directory called readme file. First type in cd readme and see whether you can access it.

![image](https://github.com/user-attachments/assets/ec0376cc-0fe3-46ee-b15e-6708fbfcfee7)

It shows you that you can't access it, so then it means that it is a file so you can view its details by typing.
<pre><code>cat readme</code></pre>

Then successfully you will get the password for the next level.Password will be <pre><code>ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If</code></pre>

![image](https://github.com/user-attachments/assets/75befae7-6578-442d-be64-44de358c73d0)

# Level 0 ----> Level 1

To go from level 0 to level 1, we need to type the code in the windows powershell as;
        <pre><code>ssh bandit1@bandit.labs.overthewire.org -p 2220 </code></pre>

Go to the site to check for any clues or tips given for the level,

![image](https://github.com/user-attachments/assets/cf0b3ebf-1849-432c-b05a-140a01287d69)

Once you access the level 1 after entering the password you got from level 1, explore the game a little more. Before exploring you should get a view of the game like this.

![image](https://github.com/user-attachments/assets/adcfe815-50b9-41f2-94e6-850f6f2cf612)

The easiest way to see the contents in the file is to go by pressing the command ls, to view the contents in the file which will then show a file - but we do not know to use which command to access the - file
![image](https://github.com/user-attachments/assets/c26b644a-9e7b-48d3-8078-e04be2f240e9)

To handle a file named dash in the windows powershell, you need to first try to access it by typing cd ./- . But will it work,let's see what kind of result we get;

This is the result we get,
![image](https://github.com/user-attachments/assets/dc94eed4-afa6-40f7-9a11-6cacd4433f72)
It says that the file we tried to access is not a directory then try to retreive the value in the file by typing the command.

<pre><code>cat ./- </code></pre>
<h3>The result we get here is shown below in the picture: </h3>

![image](https://github.com/user-attachments/assets/d5e1a014-11bf-43be-891e-588dc9d9cb85)
This gives us the password or code to the next level,

<pre><code>263JGJPfgU6LtdEvgfWU1XP5yac29mFx</code></pre>
