<h1>Mouse and Keylogger with python and Pynput</h1>

 

<h2>Description</h2>
In this project I was aiming create a program designed to track and log user input data, including keystrokes and mouse movements or clicks. The program captures and stores this input data in a file or sends it to a specified location. In this project I made use of pynput to monitor keyboard and mouse events. I am aware that this keyloggers are sensitive tools that should be used ethically, respecting privacy and with proper authorization.




<br />


<h2>Languages and Utilities Used</h2>

- <b>PyCharm</b> 
- <b>Python Terminal</b>

<h2>Environments Used </h2>

- <b>Python 3.6 on PyCharm</b> 

<h2>Project walk-through:</h2>

<p align="center">
Creating code to store keystrokes in a text file(in this case log.txt) <br/>
<img src="https://i.imgur.com/mnOY7wJ.png" height="80%" width="80%" alt="SSH lab Steps"/>
<br />
<br />
After instaling pynput, in Main we want to focus on "Listeners" to literally listen to keystrokes and also the use of the 'with' keyword to release memory.
  <br/>
<img src="https://i.imgur.com/6tvXF71.png" height="80%" width="80%" alt="SSH lab Steps"/>
<br />
<br />
I created a 'control' python file to finally write the command to control mouse-positioning, listen to mouse, controlling keyboard and listening to keyboard.
  <br/>
<img src="https://i.imgur.com/vQekdcT.png" height="80%" width="80%" alt="SSH lab Steps"/>
<br />
<br />
Now in 'main' I was able to import Listener as well as the code here to record the keystrokes on my 'log.txt' file created at the beginning. As you can see here, when running the code, when I wrote anywhere on the system, it recorded it on the file. Those letters in the log.txt file, were my keystrokes on google after i ran the code and before I stopped it.
<br />
<br />
<img src="https://i.imgur.com/Qh4VxUd.png" height="80%" width="80%" alt="SSH lab Steps"/>
 <img src="https://i.imgur.com/yoqBuOo.png" height="80%" width="80%" alt="SSH lab Steps"/>
<br />
<br />
Now here, I wanted to set a listener for the mouse instead of the keystrokes, I was able to again import the Listener with pynput but instead here it was for the mouse positioning as you can see on the code. You can see below at the terminal, the exact positioning of my mouse on the screen.
<br />
<br />
<img src="https://i.imgur.com/52JJ4OR.png" height="80%" width="80%" alt="SSH lab Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
