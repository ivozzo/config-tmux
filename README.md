# My TMUX configuration

This is my TMUX configuration, nothing special.

## TPM usage
I used [TMUX plugin manager](https://github.com/tmux-plugins/tpm) for importing [jimeh/themepack](https://github.com/jimeh/tmux-themepack) plugin.
You'll find specific plugin usage instruction in the linked repos.

## Configurations
### Managing .conf
Prefix | Command | Description
-------|---------|-----------
Yes | R | reload /etc/tmux.conf
Yes | r | reload ~/.tmux.conf
Yes | Ctrl + Return | Display ~/.tmux.conf

### Sessions
Prefix | Command | Description
-------|---------|-----------
Yes | Ctrl + S | New session
Yes | S | Kill session
Yes | s | Choose session
Yes | . | Rename session
Yes | d | Detach client
Yes | D | Choose client

### Windows
Prefix | Command | Description
-------|---------|-----------
Yes | Ctrl + w | New windows
Yes | W | Kill actual window
Yes | , | Rename windows
No | Ctrl + Left | Previous window
No | Ctrl + Right | Next Windows

**TODO**

## Keys
**TODO**

## Simplicity is the key
Jokes aside, I tried to make it as simple as possible.
You'll find a friend in 
```
<prefix> Ctrl + Return

```
This command will spawn a text editor with your source tmux.conf

# Warning
You have to modify some paths inside .tmux.conf for making it working.
Path on repo defaults to home directory (**~/.tmux**) 