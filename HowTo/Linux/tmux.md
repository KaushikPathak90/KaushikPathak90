Reference: hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/  

# TOC
1. [Installation](#installation)
2. [Sessions](#sessions)
   1. [Existing](#sessions-existing)
      1. [Checking](#sessions-existing-checking)
      2. [Attaching](#sessions-existing-attaching)
      3. [Creating](#sessions-existing-creating)
      4. [Creating with specific name](#sessions-existing-creating-name)
      5. [Renaming](#sessions-existing-renaming)
      6. [Detaching](#sessions-existing-detaching)
   2. [Windows](#sessions-windows)
      1. [Create](#sessions-windows-create)
      2. [Renaming](#sessions-windows-renaming)
      3. [Switching](#sessions-windows-switching)
      4. [Scrolling](#sessions-windows-scrolling)
      5. [Resize](#sessions-windows-resize)
      6. [Splitting](#sessions-windows-splitting)

<a name='installations'></a>
# Installation  
`sudo apt-get install tmux`  
`brew install tmux`

<a name='sessions'></a>
# Sessions

<a name='sessions-existing'></a>
## Existing

<a name='sessions-existing-checking'></a>
### Checking
`tmux ls`

<a name='sessions-existing-attaching'></a>
### Attaching
`tmux attach -t 0`

<a name='sessions-existing-creating'></a>
### Creating
`tmux`

<a name='sessions-existing-creating-name'></a>
### Creating with specific name
`tmux new -s <User-Defined-Name>`

<a name='sessions-existing-renaming'></a>
### Renaming
`tmux rename-session -t 0 <User-Defined-Name>`

<a name='sessions-existing-detaching'></a>
### Detaching
`Ctrl + b, then d`

<a name='sessions-windows'></a>
## Windows

<a name='sessions-windows-create'></a>
### Create
`Ctrl + b, then c`

<a name='sessions-windows-renaming'></a>
### Renaming
`Ctrl + b, then ,`  
`tmux rename-window <new name>`  
`tmux rename-window -t <otherwindow> <new name>`  
`Ctrl-b : rename-window <new name>`  

<a name='sessions-windows-switching'></a>
### Switching
`Ctrl + b, then p`    : Previous  
`Ctrl + b, then n`    : Next  
`Ctrl + b, then <id>` : Specific Id  

<a name='sessions-windows-scrolling'></a>
### Scrolling
`Ctrl + b, then [, then UpArrow/DownArrow`

<a name='sessions-windows-resize'></a>
### Resize
`Ctrl + b, then z`                  : Go full size, repeat to return back to previous size  
`Ctrl + b, then Ctrl + <Arrow-Key>` : Haven't tried  
`Ctrl + b, then ,`                  : Rename current window

<a name='sessions-windows-splitting'></a>
### Splitting
`Ctrl + b, then %` : Haven't tried
