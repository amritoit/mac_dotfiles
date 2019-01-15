Amritnedu: My Dot Files for macbook@freshworks


``` 

# Change into home directory
cd ~/

# Git clone this repo:
git clone git@github.com:amritoit/mac_dotfiles.git

# Create/validate existence for a file called .bashrc:
touch ~/.bashrc

# Add the thing in the quotes to the .bashrc file:
echo ". ~/mac_dotfiles/bashrc" >> ~/.bashrc

# Create/validate existence for a file called .bash_profile:
touch ~/.bash_profile

# Add the thing in quotes below to the .bash_profile file:
echo ". ~/.bashrc" >> ~/.bash_profile

# Run .bash_profile:
. ~/.bash_profile
```
