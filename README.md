# dwm-6.5-with-8-patches

The following 8 patches are included:
attachaside 
cfacts (change the horizontal split ratio)  
systray
movestack (move one program to the next or previous window) 
pertag (settings per tag/workspace) 
resizecorners (improvement for resizing window with mouse) 
rotatestack 
swallow (no terminal if not usable due to running a program without &)

All the patches which you truly need and no patch which many users don't need, except attachaside being debatable (subjective). A great foundation for starting with dwm.
Just download the tar-archive, run "tar -xvf dwm.tar" in the desired directory and then run "sudo make install". If you use a graphical loginmanager (displaymanager) then you need to create a desktopfile. Here an example of that desktopfile: 
https://bbs.archlinux.org/viewtopic.php?pid=984944#p984944
https://www.reddit.com/r/suckless/comments/jj61py/comment/gaanvez/
Simply copy those lines to your file in the path which you see there. Every displaymanager will find it that way. 
