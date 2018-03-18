# Change font in the terminal

1. Open .Xresources

        nano ~/.Xresources

2. With a `!`, comment the line setting the font:

        !URxvt.font: ...

3. Add the following line:

        URxvt*font: xft:monospace:size=14:antialias=true
        URxvt*faceName: xft:monospace:size=14:antialias=true
