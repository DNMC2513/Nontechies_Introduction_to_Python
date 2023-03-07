# First steps to code in Python


## I, How to install Python?
'A byte of Python' is the main inspiration for me to initiate this Git_repository. The author, Swaroop C.H., clearly instructed newbies to install Python step-by-step in his book's  "Installation" chapter. Click [Installation_A byte of Python]( https://python.swaroopch.com/installation.html) to access his instruction on installing Python.

> How to code in Python?
There are 2 ways for users to code in Python:
- Using the Python Interpreter Prompt.
- Using an editor or an IDE.


## II, Code in Python using Python Interpreter Prompt:
This is the most 'primitive' way for users to code in Python.

### a, Write your own code:
1. Step 1: Open the Terminal in your operating systems. Ways to open a Terminal vary across different operating systems. If you are using a Microsoft OS laptop, you can follow this guide:
- Click the `Search` button or the four-block window on the bottom bar on your screen.
- Type terminal, then press the `Enter` key.
> Shortcut key: Press the Windows + R, then choose `cmd.exe` in the drop-down box.

2. Step 2: Call out the Python prompt by typing:

```shell
Python3
```
- Then press `Enter`.
- After this step, a text like this will pop up:

```shell
Python 3.10.10 (tags/v3.10.10:aad5f6a, Feb  7 2023, 17:20:36) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

- After `>>>` is the place for users to type their code.

3. Step 3: Type down the code. If you cannot think of any code statement, type:

```shell
Print(‘Hello world”)
```

- Since this is the de-facto ritual that every coder has to go through to enter the world of Python.

### b, Run the source code:
`Source code`, put simply, is the file that contains the code that you want to execute.

1. Step1: Open the Terminal in your operating systems. Ways to open a Terminal vary across different operating systems. If you are using a Microsoft OS laptop, you can follow this guide:
- Click `Search` button or the four-block window on the bottom bar on your screen.
- Type terminal, then press `Enter` key.

> Shortcut key: Press the Windows + R, then choose `cmd.exe` in the drop-down box.

2. Step 2: Change the directory to the folder where you saved the source code:

```shell
cd <folder_path>
```

3. Step 3: Run the program by entering the command:

```shell
hello <filename.py>
```

- `.py` is one of the standard extensions (i.e. the part after '.' of the file name) for Python files. All files that contain: .py, .pyi, .pyc, .pyd, .pyo, .pyw, .pyz extensions are Python files.


## III, Using an editor or an IDE:
1. What is an editor?
 - An editor is an environment where users type down and execute their code. An instance of Python editor is IDLE. IDLE is a Python editor that comes within your Python installation. You can learn how to code on an editor with just a click: [Real Python]( https://realpython.com/python-idle/#a-file-editor)

2. Why should users use an editor instead of Python Interpreter Prompt?
- Firstly, users are prone to make mistakes while typing extensive code. An editor helps coders overcome this limitation by providing auton-indentation, syntax highlighting, etc.
- Secondly, it is impossible to save code statements and create a source code using Python Interpreter Prompt.

3. What is an IDE:
- IDE is the short form of 'Integrated Development Environment'. An IDE is a software that combines all common developer tools, such as an Editor and a Terminal, into a single Graphical-User-Interface. Some of the most common IDE(s) are: JupterLab, Pycharm, Atom
 
4. Why should users use an IDE instead of a text editor?
- An editor is great (at least compared to Python Prompt Interpreter). However, an IDE is better. Being able to access all tools you need on the same interface or just a click away can save users tons of time, as well as other conveniences.

 


