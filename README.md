# devtools
######################################## zsh installation and configuration#######################################
#install zsh
sudo apt install zsh

#make zsh as your default shell

sudo chsh -s `which zsh` <username>

#restart
sudo shutdown -r 0

#Now download the installer script and execute it.
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh

#copy configuration file to origin directory
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
source ~/.zshrc
