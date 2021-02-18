# Brew
# Mate

# iTerm2
## Oh My Zsh
1. [Power Level 10k](https://github.com/romkatv/powerlevel10k/blob/master/README.md)
	`git clone --depth=1 https://gitee.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
	
	In `~/.zshrc`set `ZSH_THEME="powerlevel10k/powerlevel10k"`

2. [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) 
	Clone this repository into $ZSH_CUSTOM/plugins (by default ~/.oh-my-zsh/custom/plugins)
	
	`git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
	
	Add the plugin to the list of plugins for Oh My Zsh to load (inside ~/.zshrc):
	`plugins=(zsh-autosuggestions)`

3. [zsh-autocompletions](https://github.com/zsh-users/zsh-completions)
	Clone the repository inside your oh-my-zsh repo:
	`git clone https://github.com/zsh-users/zsh-completions ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/zsh-completions`
	
	Enable it in your .zshrc by adding it to your plugin list and reloading the completion:
	`plugins=(… zsh-completions)`
	
	`autoload -U compinit && compinit`

4. [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

## Other Plugins
1. [autojump](https://github.com/wting/autojump)
	`brew install autojump`
