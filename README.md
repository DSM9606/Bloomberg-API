# Bloomberg-API

Bloomberg API Test Project

# Dan Martin Rocks Bloomberg-API README FILE  07.01.21


##### Instructions: write the appropriate setup instructions, and the exact conda, pip, and python commands needed to run the program 


## Part I: Navigate to the correct folder in Terminal:


**HINT: Navigate to the Rocks, Paper, Scissors App in the terminal by first typing "pwd enter" into terminal to find your present working directory and then "ls -al" to find all of the folders in your current directory also "cd .." to go to the previous enclosing folder if you went into the wrong folder**

> ## Important! My rocks, paper scissors app is on my desktop and is in a folder called: <i> " </i>

> ## The location of the program on my computer is: <i> /Users/martinhsu/desktop/Bloomberg-API <i/>


When I open terminal to get to the correct folder holding the program I type commands in this order to navigate to the correct folder:

#### Step 1: Type "pwd" + ENTER -> users/martinhsu
#### Step 2: Type "cd desktop" + ENTER 
#### Step 3: Type "cd Bloomberg-API" + ENTER
#### Step 4: Type "pwd " + ENTER to make sure you have opened the folder Bloomberg-API on the desktop
#### NOTE: After completing these steps in terminal my present working directory (pwd ENTER) was <i> /Users/martinhsu/desktop/Bloomberg-API </i>

## Part II: Set up a new virtual environment
#### Step 1: Type "conda create -n bloom-env python=3.8" + ENTER in the terminal application
#### Step 2: Type "y" + ENTER two times accept terminal conditions

#### Step 3: Type "conda activate bloom-env" + ENTER 

## Part III: Make sure your packages are installed
#### Step 1: Type "pip install -r requirements.txt" + ENTER into terminal
#### Step 2: Type "pip list" + ENTER into terminal

#### Note to make bloomberg connect to the API please reference

##### Two critical packages are:
##### python -m pip install --index-url=https://bcms.bloomberg.com/pip/simple blpapi

#### python -m pip install xbbg

##### https://www.bloomberg.com/professional/support/api-library/

##### https://www.youtube.com/watch?v=jyJ3tHGgFXk
