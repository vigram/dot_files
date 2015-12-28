dotfiles are helping you to personalize your system

## Install

* Clone the repo: git clone https://github.com/vigram/dot_files.git ~/dot_files

* Create couple of symbolic links:

  - $ ln -s ~/dot_files/my_zshrc ~/.zshrc
  - $ ln -s ~/dot_files/irbrc ~/.irbrc
  - $ ln -s ~/dot_files/gitconfig ~/.gitconfig
  - $ mkdir ~/bin (if bin directory doesn't exist)
  - $ ln -s ~/dot_files/sake ~/bin/sake
  - $ ln -s ~/dot_files/screenrc ~/.screenrc

* Modify ~/dot_files/my_zshrc 
  
  You may have to modify the my_zshrc file to your liking a bit. The PATH and 
  other stuff is configured according to the way, I have setup my machine.You may need to
  change that.

* Install ZSH shell:
  - $ sudo apt-get install zsh

* Switch to zsh:  
  $ chsh -s /bin/zsh
     If chsh doesn't work then open ~/.bashrc file and add "zsh" at end  

* Close the terminal
* Logout from your active session. 
* Open terminal and voila, you should have zsh with new prompt and everything working.
