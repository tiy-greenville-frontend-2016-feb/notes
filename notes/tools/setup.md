# Setup

* * *

Some of the following tools require the use of the terminal (Terminal.app). This
can be quite overwhelming if you've never used it before, but don't worry,
you'll soon grow comfortable with it.

## Development Tools

### Install script

A custom install script can be used to install all of the developer tools you
will need for the class.  To run the install script:


1. Open Terminal.app
2. In the terminal, type `xcode-select --install` and follow the on screen
   instructions.
3. Download [the
   script](https://gist.githubusercontent.com/jacobthemyth/6cd361c1e63c819e415e/raw/9f4095629d2f93ecf4b130f488a05983aaa78459/install-script.sh)
   to your Desktop by going to File > Save As and saving it as
   `install-script.sh` on your Desktop.
4. In the terminal, navigate to your Desktop by typing `cd ~/Desktop` at the
   prompt
5. Make the script runnable by typing `chmod 755 install-script.sh` at the
   prompt (this won't produce any visible change).
6. Run the script by typing `./install-script.sh` at the prompt.

### Creating an SSH key

You'll need an SSH key when using Github. SSH keys are a way to identify trusted
computers, without involving passwords. Walk through the steps in the following
tutorial to create your SSH key and add it to your Github account:
[https://help.github.com/articles/generating-ssh-keys](https://help.github.com/articles/generating-ssh-keys)
