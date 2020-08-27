## Using LearnPython.org

This document describes how to use the <https://LearnPython.org> interactive tutorials to learn about Python language features and programming.

### First Interactive Tutorial: Hello, World!

Go to <https://www.learnpython.org/en/Welcome> and look for [Hello, World!](https://www.learnpython.org/en/Hello%2C_World%21?raw=true) listed under *Learn the Basics*. The following screen should be displayed.

![Hello, World!](https://raw.githubusercontent.com/dalemusser/python1/master/LearnPython/Hello%20World/Hello%20World%20full.png)

The python code is provided in a text area that has the label ```script.py``` in the tab at the top as shown in the following.

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/Hello%20World%20script.png?raw=true)

To run the code in ```script.py```, click on the gold **Run** button. Momentarily, next to the button, "Setting Up Workspace" is displayed followed by "Executing..." (very quickly...you may not see it) and then "Workspace Ready". When the code has run, the ```iPython Shell``` tab becomes active and shows the output of the program like shown in the following.

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/Hello%20World%20shell.png?raw=true)

The code that is provided in ```script.py``` can be edited and then run so you can experiment, which you are highly encouraged to do. The following shows that I replaced the string "This line will be printed." with "My name is Dale.".

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/Hello%20World%20edit%20script.png?raw=true)

And, now that I've edited it, when I run it I get the following.

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/Hello%20world%20run%20edited%20script.png?raw=true)

The "This line will be printed." is there from the first time I ran the code. The "My name is Dale." is there from the second time I ran the code after editing the string that is printed.

> **You are strongly encouraged to experiment and play with the code in each example.**

After the first item, scroll down to the next one titled **Indentation** and work with it as provided. Observe the code, try to determine what it will do, then run the code to see the result. After that, make modifications to the code to try new things and test whether or not those modifications work and yield the intended result.

The original code provided in the **Indentation** item was:

```
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
```

When run, it prints out: "x is 1." because x is set to 1 before the ```if x == 1```.

I then modified the code to handle the case where x is not 1 and set the value of x to 2 as shown below. 

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/Hello%20World%20Indentation%20script.png?raw=true)

When the code is run, the following is displayed.

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/Hello%20World%20Indentation%20shell.png?raw=true)

The "x is 1." is from the first run of the code before it was modified.  The "x is not 1." is from the second run of the code after it was modified to set x to 2 and added an else condition to the if statement.

You can CLEAR the iPython Shell to remove information that was previously displayed.  On a macOS computer, use cmd-l.  That is, hold the cmd key down and press the l key. On a Windows computer, use ctrl-l.  That is, hold the ctrl key down and press the l key. (l is a lower case L.)

If the code in ```script.py``` contains an error and it is run, an error message is displayed in the iPython shell. The following is the previous script for the **Indentation** item, but with an incomplete print statement. It should be ```print("x is 1.")``` but it is ```print("x is 1```.  Since there is no closing quote or parenthesis, python won't know where the string in the print or the print statement ends and this causes a syntax error.

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/script%20with%20error.png?raw=true)

The following is the error displayed when the code above is run.

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/syntax%20error%20in%20shell.png?raw=true)

According to the error message, the error is on line 4 and the place in the line where it has a problem is indicated with a ^. It then states that a [syntax error](https://en.wikipedia.org/wiki/Syntax_error) occurred with the message "EOL while scanning string literal". EOL means "end of line".  That is, it reached the end of the line before it found the end of the string.  

By the way... ```<stdin>``` means "standard input". See: <https://en.wikipedia.org/wiki/Standard_streams>. A program is usually in a file (.py file) and python reads the lines of code from a file. But, in the case of the python code on this web page, the code of the program is sent to a server for processing and is provided to the standard input, ```<stdin>``` , of the program on the remote server whose job it is to run the python program and send the result back to the web page.

A tutorial may present one or more example items and then an **Exercise**. For the exercises you are asked to meet specified requirements by modifying or entering code.  You are to do the exercises to practice and assess the topics being learned.

Being able to enter python code directly into a text area on the web page and run it makes it easier to learn. But, don't forget that to write Python programs on your computer you need to create python .py files in a plain text editor, which Python IDLE provides. You can use Python IDLE to create the .py file and run it as shown below. The code from the **Indentation** example was entered in a file called ``indentation.py`` using the editor in IDLE and then it was run by choosing Run Module from the Run menu in IDLE. The web site provides a way for you to test and experiment with python code, but it is not the place where you are to write your programs for this class.

![](https://github.com/dalemusser/python1/blob/master/LearnPython/Hello%20World/Indentation%20in%20IDLE.png?raw=true)

Don't just work with the code on <https://LearnPython.org>. Enter code into .py files and run them using IDLE.

>&copy; 2020 [Dale Musser](https://dalemusser.com). All rights reserved.<br /><br />
>This document is provided with the materials for an educational course and are meant for personal use by the student while participating in the course.

![Dale Musser](https://github.com/dalemusser/common/blob/master/dalemusser/DaleMusserBWCircle200x.jpg?raw=true)