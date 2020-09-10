# vimrc
Repo is used to store my vimrc setting file and document other useful vim tricks


# Vim Tips and Tricks I pick up:

When pasting from system clipboard into vim
1. :set paste
2. insert mode
3. Right click, paste it
4. exit insert
5. :set no paste

For Ubuntu and likely for other Distros - /usr/share/vim has a vimrc file that looks for a local vimrc.local file in /etc/vim/

For my Raspberry Pi 0, I need to put the vimrc file in /etc/vim/ and the file is called vimrc (.vimrc doesn't work)
I have my vimrc repo underneath /home/vimrc because I thought that's where it needed to go but it doesnt source from there
