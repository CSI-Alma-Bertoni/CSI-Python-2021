<div style="text-align:center">
        <img    src="../../images/csi.png" 
                title="Colegio San Ignacio" 
                width="20%" 
                height="20%" />
</div>
<br>

# Module 2: Using Visual Studio Code

### Create a commit merging master into your current branch. `(1pts)`

<br>

### Open Visual Studio Code. Your first task is to change your working directory to that of the course.

1. Go to File > Open Folder
2. Select the directory you cloned your repository into `(CSI-Python-2021)`. 

<br>

### The first thing you will see on the left-most side of visual studio code is the file system for the class.
<img    src="VSLeftPanel.png" 
        title="Files available on the directory may vary from the time of the screenshot" 
        width="70%" 
        height="70%" />

<br>

### On the bottom of your screen is the Terminal. Through here you may communicate directly with your computer's Operating System. 
<br>
<img    src="Terminal.png" 
        title="Terminal" 
        width="80%" 
        height="80%" />

# Communicate with Console

## Lets start by navigating through directories 
### Type the following commands into your console


`dir` will Show contents of current directory
 
`cd ..` will take you back one directory

`cd CSI-Python-2021` will bring you back to the project directory (Assuming you went back one directory in the step before)

**(Hint)** After typing "`cd `" into the console you may hit the `TAB` key to run through the options available in the directory, or to autocomplete.

`cd Modules\Module2` will move you from
> C:\Users\user\Documents\CSI-Python-2021

to 

> C:\Users\user\Documents\CSI-Python-2021\Modules\Module2

<br>

# Interact with Python.

Python should have been installed and added to PATH. To verify this run: `python --version` and recieve an output of:
 
>Python 3.9.6

<br>

## Open Python Console

Typing `python` into the terminal will enter the Python console:

> Type "help", "copyright", "credits" or "license" for more information.
>
> \>\>\>

`print("Hello World!")` will run a simple python command that returns whichever string of text you have encapsulated into your doublequotes. In this case 
> Hello World!

`exit()` will bring you back into your Operating System's console.

<br>

## Execute Python Script
### Navigate to the Module2 directory and type: `python HelloWorld.py`. This will execute a python script.

### The output should look similar to this:

<img    src="HelloWorldSample.png" 
        title="HelloCarlos!" 
        width="80%" 
        height="80%" />

### Take a screenshot of your terminal's output showing the same elements as above. 
* #### Save it in the <u>Module2</u> directory of your branch. 
* #### Name the file using the following convention: `CSI-Carlos-Cobian-Module2-1.png`
* #### On Windows use CTRL+SHFT+S to make a selection.

### Commit and push this image before the next lecture`(2pts)`

<br>

# Class Discussion
## Answer the questions on the Markdown file located within your `Module2` directory (Module2.md). `(4pts)`

<!-- This is a comment. It is not processed by the code -->
<!-- Welcome! These are your questions. -->
<!-- Answer using full sentences to receive all points. -->
<!-- 

What does "cd" stand for?

 - Answer:

Did you get stuck at any point or cecome confused with your console? (yes/no) 
If so, what happened? How did you solve it? (optional)

 - Answer:

Did you consider searching google for other commands to run? What did you try? 

 - Answer:

What would you like to program? 

 - Answer:

Lackluster responses may result in point deductions.
-->

* ### Save the file. Commit your changes and push them to your remote repository by the end of the class. `(1pts)`
* ### You may complete the answers by issuing aditional commits and pushing them before the next class.