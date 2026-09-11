# ARAS-reports
The latex reports for the course Applied Robotics and Autonomous Systems

# Compiler
You'll need a latex compiler. For example:
TexLive:
```bash
sudo apt install texlive-full
```
Note that the `full` version is quiet big. You may also just `sudo apt install texlive` but you may be missing packages in which case you need to install them later.

# Editor
You can use whatever latex editor you prefer but I can recommend the "LaTeX Workshop" vscode extension.  
- Now a "play button" will appear when you open a .tex file. Pushing it will compile it. Creating a .pdf file (and some auxiliary files). But what's better, is that now every time you make changes in .tex, it automatically updates the .pdf file.  
So it's useful to open them side by side.  
- You can also `Ctrl+Click` in the pdf and your cursor in the .tex file will jump to the corresponding point.  
It also works the other way around with `Ctrl+Alt+J`.
- Errors and warnings can be found in the "Problems" panel (`Ctrl+Shift+M`). Additionally problems will also be highlighted in the .tex file.