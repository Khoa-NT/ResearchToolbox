# Development Tools


<!--  -->
## GitHub

- Learn Git: [Link](https://github.com/git-guides)
- Git cheat sheet: [from Prof.Francisco Martín Rico](Git/src/cheat_sheet_1.pdf)
- Download only the subdirectory of interest 
([Source](https://github.com/google-research/google-research/blob/master/README.md)): 
Open VSCode in browser by pressing `.`, then download the subdirectory from navigation panel.



<!--  -->
## VSCode
### Setup
- Connect to remote server: [Link](https://code.visualstudio.com/docs/remote/ssh)

### Trick
- Open VSCODE in browser from GitHub: Press `.`
- Master VS Code's keyboard shortcuts in 13 minutes: [Video](https://www.youtube.com/watch?v=nWIRJBCjls8)
- Open Tensorboard:  
    - Run `tensorboard --bind_all --reload_multifile True --samples_per_plugin images=300 --logdir=. --port <your_port>`
    - Then go to tab `Ports` in VSCode, and add `<your_port>`  
    - Open web browser and go to `http://localhost:<your_port>`  



<!--  -->
## Tmux

- Website: [Link](https://github.com/tmux/tmux/wiki)
- Getting Started: [Link](https://github.com/tmux/tmux/wiki/Getting-Started)
- Cheat Sheet: [Link](https://gist.github.com/MohamedAlaa/2961058)

Useful commands:
- `C-b d` Detach from tmux session.
- `C-b %` Split pane vertically.
- `C-b "` Split pane horizontally.
- `C-b arrow_key` Move around panes.
- `C-b z` Toggle between pane and full screen.
- `C-b c` Create a new pane.
- `C-b x` or `C-b &` Close the current pane.
- `C-b E` Spreads panes out evenly.
- `C-b space` one-time spread panes out evenly.
- `C-b [0-9]` Switch to pane `0-9`.
- `C-b s` Show all panes. `q` to quit.
- `C-b q` Show pane number.




<!--  -->
## Python

### breakpoint()

When you're inside the pdb prompt ((Pdb)), you can type commands like:

| Command | Description |
|---------|-------------|
| `h` | Help (list all commands) |
| `n` | Next line (step over) |
| `s` | Step into function |
| `c` | Continue execution |
| `q` | Quit the debugger |
| `p x` | Print the value of variable x |
| `l` | List source code near the line |


<!--  -->
## PyTorch

### Tools
Use [PyTorch Landscape](https://landscape.pytorch.org/) to find the best tools for your project ([Pytorch Blog](https://pytorch.org/blog/pytorch-landscape/)).
Note that some tools are set as `archived` in the landscape but are still active and useful.

### Tensorboard
- Tutorial: [Link](https://pytorch.org/docs/stable/tensorboard.html)


