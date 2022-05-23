# The Coder's Computer

## Setting up on Windows 10

### WSL Version 2 and the Ubuntu app
 1. Most recent verson of windows is recommended
 2. Need to enable:
    1. Virtual Machine Platform
    2. Windows Hypervisor Platform
    3. Windows Subsystem for Linux
 3. Run (wsl --set-default-version 2) in powershell
 4. Install Ubuntu, found on the windows store. (On opening, location should be /home/<your username>)
 5. Verify that you are running WSL Version 2 by running "wsl -l -v"
  
  ### Backups
  
  1. Run:
  - mv ~/.bashrc .bashrc.bak
  - mv ~/.bash_profile .bash_profile.bak
  - mv ~/.profile .profile.bak
  - mv ~/.zshrc .zshrc.bak
  2. Run "sudo apt-get install zsh" then type "zsh" and choose option 0
  
  ### Installing Linux App Manager
 1. Type "sudo apt-get update".
 2. type "sudo apt-get upgrade". Press y when prompted.
 3. type "sudo apt autoremove". This will remove any packages that are no longer needed.
 4. Install the “Build Essentials” kit by typing "sudo apt-get install build-essential"

  ### Installing Homebrew
  1. type "/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  2. type "test -d ~/.linuxbrew && eval $(~/.linuxbrew/bin/brew shellenv)" then "test -d /home/linuxbrew/.linuxbrew && eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
