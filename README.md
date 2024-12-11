# Corrupt-ZSH-History-FIX
Run this script as root to fix corrupt zsh history error.

# **Installation**

1. git clone https://github.com/thunderict/Corrupt-ZSH-History-FIX.git
2. mkdir ~/bin
3. cd ~/bin
4. mv ~/Corrupt-ZSH-History-FIX/zshfix ~/bin
5. cd ~
6. sudo nano .zshrc
7. add this line at the end of the file export PATH="$HOME/bin:$PATH" and ctrl+x, and save the name as .zshrc and overwrite.
8. cd ~/bin
9. chmod +x zshfix

Now you can cd into ~ and run the script. zshfix will instantly fix it.

# Enjoy!
