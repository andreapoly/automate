# automate

This repo contains some useful scripts to automate the daily, repetitive
actions so you don't need to type them in again and again :D

# Installation
## Prerequisites
### Scripts Folder
Most of the times, the scripts in a UNIX systems for a user should lie in
the `/Users/$USER/.local/bin/` directory.
Check if the directory is already present for your user:
```bash
ls /Users/$USER/.local/bin/
```
If it's not there, you can just create it:
```bash
mkdir -p /Users/$USER/.local/bin/
chmod -R 700 /Users/$USER/.local/bin/
```
Now, try to run the `ls` command above again and check that the directory exists.
Add this folder to your system `PATH` in your system shell file.
For example, if you're using Zsh, simply open your `~/.zshrc` and add this line:
```bash
export PATH="/Users/$USER/.local/bin:$PATH"
```

### Clone this repo
Simply type in - in a directory of your choice:
```bash
git clone https://github.com/andreapoly/automate.git
```

## Install a script
Every script lying in this repository be easily installed by copying its content
from this directory to the `/Users/$USER/.local/bin/` one.

To do that, simply type in:
```bash
cp ./<SCRIPT> /Users/$USER/.local/bin/<SCRIPT>
```
replacing `<SCRIPT>` with the script of your choice.
You should now be able to run the script anywhere!