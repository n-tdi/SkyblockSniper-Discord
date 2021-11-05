# SkyblockSniper-Discord
a simple skyblock sniper in python with discord webhook intergration

# How to use:

### Step 1
Download Python 3.9.7. There's literally thousands of guides on how to do this so I'll assume you can figure it out yourself. 

### Step 2
Either download this repository or just copy paste all the code from inside `main.py` into a new file on your computer called `SkyblockSniper.py`, and all the text from `requirements.txt` into a new file on your computer called `requirements.txt`.

### Step 3
Run the command `pip install -r <path to requirements.txt>` in the command prompt (Window key + R, type cmd). For example, on my computer, the path to `requirements.txt` is `C:\Downloads\requirements.txt`, so I'd use `pip install -r C:\Downloads\requirements.txt`.

### Step 4
Run the file `main.py` by going into command prompt and running the command `python <path to main.py>`. For example, on my computer, the path to `main.py` is `C:\Downloads\main.py`, so I'd use `python C:\Downloads\main.py`.

### Step 5
Now the script is running good and well. From here, you can just AFK on your island splitscreened watching Netflix or something. As soon as the script finds a good flip, you'll hear a low frequency beep for half a second, and the command to go to the auction is automatically put on your clipboard.

All you have to do is Ctrl+V every time you hear the beep, make sure it's not a scam (sometimes this happens with cosmetics or other market manipulation; can be prevented with NEU's average AH price thing), and then buy it.

## Basic Troubleshooting
> 'pip' is not recognized as an internal or external command, operable program or batch file.
>
Follow the first reply to [this stackoverflow post](https://stackoverflow.com/questions/23708898/), note that you'll have to open a new cmd window to apply the changes to PATH

> Python was not found; run without arguments to install from the Microsoft Store, or disable this shortcut from Settings > Manage App Execution Aliases
> 
Make sure Python's installation folder was added to your PATH variables properly, and follow the [other suggestions on this stackoverflow post](https://stackoverflow.com/questions/65348890/).

