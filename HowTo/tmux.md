Reference: hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/  

# Installation  
`sudo apt-get install tmux`  
`brew install tmux`

# Sessions

## Existing

### Checking
`tmux ls`

### Attaching
`tmux attach -t 0`

### Creating
`tmux`

### Creating with specific name
`tmux new -s <User-Defined-Name>`

### Renaming
`tmux rename-session -t 0 <User-Defined-Name>`

## Windows

### Create
`Ctrl + b, then c`

### Switching
`Ctrl + b, then p`    : Previous  
`Ctrl + b, then n`    : Next  
`Ctrl + b, then <id>` : Specific Id  

### Resize
`Ctrl + b, then z`                  : Go full size, repeat to return back to previous size  
`Ctrl + b, then Ctrl + <Arrow-Key>` : Haven't tried  
`Ctrl + b, then ,`                  : Rename current window

### Splitting
`Ctrl + b, then %` : Haven't tried
