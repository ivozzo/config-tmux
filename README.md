# My TMUX configuration

This is my TMUX configuration, nothing special.

## TPM usage
I used [TMUX plugin manager](https://github.com/tmux-plugins/tpm) for importing [jimeh/themepack](https://github.com/jimeh/tmux-themepack) plugin.
You'll find specific plugin usage instruction in the linked repos.

## Miscellaneous
You can summon command-prompt with:
```
<prefix> :
```

You can open ranger (if installed) with:
```
<prefix> +
```
this will result in a vertical split

## Configurations
### Managing .conf
Prefix | Command | Description
-------|---------|-----------
Yes | R | reload /etc/tmux.conf
Yes | r | reload ~/.tmux.conf
Yes | Ctrl + Return | open ~/.tmux.conf

### Sessions
Prefix | Command | Description
-------|---------|-----------
Yes | Ctrl + q | new session
Yes | S | kill session
Yes | s | choose session
Yes | . | rename session
Yes | d | detach client
Yes | D | choose client

### Windows
Prefix | Command | Description
-------|---------|-----------
Yes | Ctrl + w | new window
Yes | W | kill actual window
Yes | , | rename window
No | Ctrl + p | previous window
No | Ctrl + n | next Windows

### Panes
Prefix | Command | Description
-------|---------|-----------
Yes | h | split window vertically
Yes | v | split window horizontally
No | Shift + Left | resize pane
No | Shift + Right | resize pane
No | Shift + Up | resize pane
No | Shift + Down | resize pane
Yes | z | zoom pane (full view, toggle)
Yes | q | display panes
Yes | K | kill pane
Yes | Up | select upper pane
Yes | Down | select bottom pane
Yes | Left | select left pane
Yes | Right | select right pane

### Miscellaneous
Prefix | Command | Description
-------|---------|-----------
Yes | Ctrl + d | opens a docker monitoring session (watch on docker ps, images, networks, volumes and a bash)

## Simplicity is the key
Jokes aside, I tried to make it as simple as possible.
You'll find a friend in 
```
<prefix> Ctrl + Return

```
This command will spawn a text editor with your source tmux.conf

# Warning
You have to modify some paths inside .tmux.conf for making it working.
Path on repo defaults to home directory (**~/.config/tmux**) 
