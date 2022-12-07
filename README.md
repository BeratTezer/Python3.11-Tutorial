# <p align="center"> ![kisspng-professional-python-programmer-computer-programmin-python-logo-download-5b47725c1cc0d6 3474912915314089881178-removebg-preview](https://user-images.githubusercontent.com/64587561/205902584-a348bd03-8884-40cd-82ef-6c3b55acaf02.png)Learn Python!![kisspng-professional-python-programmer-computer-programmin-python-logo-download-5b47725c1cc0d6 3474912915314089881178-removebg-preview](https://user-images.githubusercontent.com/64587561/205902584-a348bd03-8884-40cd-82ef-6c3b55acaf02.png) </p>

<p align="center">
<img src="https://img.shields.io/badge/Situation-Updating...-green" alt="situation bagde"/> <img src="https://visitor-badge.glitch.me/badge?page_id=BeratTezer.Python3.11-Tutorial&left_text=Viewers%20of%20Education" alt="visitor badge"/> <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/BeratTezer/Python3.11-Tutorial?color=informational&label=Thanks%20to%20me"> 
</p>

## 📅 Contents

- [VSCode and Python Extension](#-vscode-and-python-extension)
- [Let's Start!](#-lets-start)
- [First Lines](#-first-lines)

## 📦 VSCode and Python Extension

### 1) Install VSCode
> Firstly, we need to download Visual Studio Code. Visual Studio Code is a streamlined code editor with support for development operations like debugging, task running, and version control. Go to the website: https://code.visualstudio.com/Download
<p align="center">
  <img src="https://user-images.githubusercontent.com/64587561/205915207-dff76564-e8ec-4e5c-b5e3-dae6db250838.png" alt="Download VSCode"> 
</p>

### 2) Install Python 3.11
> Secondly, we need to download Python. Python is an interpreted, object-oriented, high-level programming language with dynamic semantics developed by Guido van Rossum. We download it to use this software language on our device. Go to the website: https://www.python.org/downloads/
<p align="center">
  <img src="https://user-images.githubusercontent.com/64587561/205915774-d5fbbc45-143e-4b77-a933-4128da5d8cb7.png" alt="Download Python">
</p>

### 3) Install Python Extension to VSCode
> Last step: install python extension to VSCode. This allowed us to write, run and debug python commands on VSCode. To do this step, you can watch the video or follow the images. Video link: www.youtube.com

<p align="center">
  <b>Step 1:</b> Click Extentions Icon
  <img src="https://user-images.githubusercontent.com/64587561/205919240-64291d09-31bc-47af-a01a-f10075c56172.png" alt="Download Python Extension">
</p>
<p align="center">
  <b>Step 2:</b> Write Python to the Search Box
  <img src="https://user-images.githubusercontent.com/64587561/205920013-43e751cf-bf56-4df0-9972-43a5c0468916.png" alt="Download Python Extension">
</p>
<p align="center">
  <b>Step 3:</b> Install the Python Extension
  <img src="https://user-images.githubusercontent.com/64587561/205920591-4fd77e3b-9801-4fa6-bf01-be7d9370824f.png" alt="Download Python Extension">
</p>


## 🦉 Let's Start!

> In this section, I will write and show some code lines one by one. You will see examples and explanations and if you want to get the code, you can reach them above. 

### Create a Python (.py) File

<p align="center">
  <b>Step 1:</b> Click the Open Folder Button<br>
  <b>Step 2:</b> Create a Folder
  <img src="https://user-images.githubusercontent.com/64587561/206039795-4b373fa2-df43-4b9b-9961-8cf33c106a3b.png" alt="Create a Python Folder">
</p>

<p align="center">
  <b>Step 3:</b> Click the button<br>
  <b>Step 4:</b> Write a name for file and end it with ".py" (<code>example_name.py</code>)
  <img src="https://user-images.githubusercontent.com/64587561/206041026-256073f3-027d-4659-840e-6c6abe65b3cc.png" alt="Create a Python File">
</p>

<p align="center">
  <b>Step 5:</b> Sit back and realize you're ready! 😁
  <img src="https://user-images.githubusercontent.com/64587561/206042746-3270b832-b851-40e6-a516-c482dc954634.png" alt="Download Python Extension">
</p>

## 🐱‍👤 First Lines

### 1) <code>print</code>
> Uses to output to the screen. Usage:

```
  print("Can you hear me?")
```
> This will write <code>Can you hear me?</code> to the terminal

### 2) <code>input</code>
> It allows us to use it in the program by entering data from the terminal

```
  input("Write your name: ")
```
> This will write <code>Write your name: </code> and will wait until you write anything

### 3) <code>if</code>
> It allows us to create condition block

```
  if 5 > 2:
    print("This is true!")
```
> This will write <code>This is true!</code> because <i>if</i> condition is right (As we know, 5 is bigger than 2). So how do we do it if it's wrong?

### 4) <code>if-else</code>
> It allows us to create condition block

```
  if 2 > 5:
    print("This is true!")
  else:
    print("This isn't true!")
```
> This will write <code>This isn't true!</code> because <i>if</i> condition isn't right (As we know, 2 isn't bigger than 5). So how do we do it if it's equal?

### 5) <code>if-elif-else</code>
> It allows us to create condition block with different possibilities

```
  if 2 > 2:
    print("This is true!")
  elif 2 == 2:
    print("They are equal")
  else:
    print("This isn't true!")
```
> This will write <code>They are equal</code> because <i>if</i> condition isn't right and <i>elif</i> is right. (As we know, 2 equal 2 😁). So how do we do cheack them? For example we used "==" in our "elif" section. Before talk about them, I need to show one more thing.

### 6) <code>if-elif-...-elif-else</code>
> It allows us to create condition block with more different possibilities

```
  if 2 > 2:
    print("This is true!")
  elif 2 == 2:
    print("They are equal")
  .
  .
  .
  elif 2 != 2:
    print("They aren't equal")
  else:
    print("This isn't true!")
```
> This will write <code>They aren't equal</code> because <i>if-second elif</i> condition isn't right and <i>first elif</i> is right. We used "!=" in our "elif" section. As the other example, we can check some conditions. These "==" and "!=" some examples of what we use.
> > Until now, you learned the print something to the screen, you learned to use input and you see the if-elif-else condition blocks. 
> > > To learn and understand these blocks too, we need to learn something more 😄

// örnekler öncesi operations ve variable types başlıkları oluştur
