# dev-start
 A script for starting all the programs I use when writing code

To fully utilize this script I created a batch file that would allow
me to quickly open the three programs I use most often when coding.

The way I did this was:

1. I created a notepad file that held two things:
    Where my python exe was stored (in this case it was "C:\Users\Connor\AppData\Local\Programs\Python\Python37-32\python.exe")
    Where the script I wanted to run was stored ("C:\Code\dev-start")

    My txt file ended up looking like this:

    "C:\Users\Connor\AppData\Local\Programs\Python\Python37-32\python.exe" "C:\Users\Connor\Documents\Coding\dev-start.py"
    pause

    (If you're wanting to recreate this, make sure you don't ommit the quotes around where your python and script is held)

2. Saved the .txt file as a .bat file to my desktop

What this did was create a single icon that would allow me to easily open all three files efficiently. 