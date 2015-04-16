#Vim Runtime Configuration


## Shortcuts

### Vim Boostrap

Command | Description
--- | ---
`:cd <path>` | Open path */path*
`<Control+w>+arrows` | Navigate via split panels
`<Control>+w+w` | Alternative navigate vim split panels
`,.` | Set path working directory
`,w or ,x` | Next buffer navigate
`,q or ,z` | previous buffer navigate
`SHIFT+t` | Create a tab
`TAB` | next tab navigate
`SHIFT+TAB` | previous tab navigate
`,e` | Find and open files
`,b` | Find file on buffer (open file)
`,c` | Close active buffer (clone file)
`F2`  | Open tree navigate in actual opened file
`F3`  | Open/Close tree navigate files
`F4` | List all class and method, support for python, go, lua, ruby and php
`,v` | Split vertical
`,h` | Split horizontal
`,f` | Search in the project
`,o` | Open github file/line (website), if used git in **github**
`,sh` | Open shell.vim terminal inside Vim or NeoVim built-in terminal
`,ga` | Execute *git add* on current file
`,gc` | git commit (splits window to write commit message)
`,gsh` | git push
`,gll` | git pull
`,gs` | git status
`,gb` | git blame
`,gd` | git diff
`,gr` | git remove
`,so` | Open Session
`,ss` | Save Session
`,sd` | Delete Session
`,sc` | Close Session
`>` | indent to right
`<` | indent to left
`gc` | Comment or uncomment lines that {motion} moves over
`YY` | Copy to clipboard
`P` | Paste
`<Control+y>,` | Activate Emmet plugin

#### Python hotkeys

Command | Description
--- | ---
`SHIFT+k` | Open documentation
`Control+Space` | Autocomplete
`,d` | Go to the Class/Method definition
`,r` | Rename object definition
`,n` | Show where command is usage


### System

Command | Description
--- | ---
`:so $MYVIMRC` | reload .vimrc
`:so %` | reload .vimrc when editing
