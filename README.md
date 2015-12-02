# chi.zsh-theme

## v2

A ZSH theme built for people who want:
  * Simple Terminal (I use iTerms)
  * Git Status for each working folder

For Mac Users, I highly recommend iTerm 2 + Afterglow for Sublime Text

### ScreenShots
![Screenshot 1](images/Screen%20Shot%202015-07-03%20at%2001.13.41.png)
![Screenshot 1](images/Screen%20Shot%202015-07-03%20at%2001.14.40.png)

### What does it show?

 * 🕕 Time
 * `~/Desktop` Working directory
 * > where you type your cmds
 * Git Status
  * `✹git:master` **color : Red** unstaged commit
  *  `git:master` **color: White** committed files
  * `○` shows if current directory is a git folder || git branch


### How To Install

#### [oh-my-zsh](http://ohmyz.sh/)

1. [Download](https://github.com/andela-abankole/chi/archive/master.zip) || Clone the URL
2. Copy **themes** folder that contains `chi.zsh-theme`
3. Open Terminal, enter `defaults write com.apple.finder AppleShowAllFiles YES` to show hidden files and folders
4. Go to your home directory and find `.oh-my-zsh` folder, right click and open in new tab, enter the custom folder
5. Paste the **themes** folder you copied into the custom folder and close finder
6. Enter your oh-my-zsh configuration file by entering `vi ~/.zshrc`, and press **i** key to enter edit mode
7. Change your current theme `ZSH_THEME="robbyrussell"` to `ZSH_THEME="chi"`, and press **esc** key to leave edit mode
8. Press `:wq` to leave **Vi** mode
9. Enter `source ~/.zshrc` to save the configuration
10. Done, Enjoy your new theme!!

#### [zgen](https://github.com/tarjoilija/zgen)

1. Add `zgen load andela-abankole/chi themes` to your `.zshrc` with your other `zgen load` commands
2. `zgen save` to create a new `init.zsh`
3. start a new iTerm window to load the new configuration.
