# cmus-lyrics

## Description

Fetch lyrics of currently playing music in cmus. All lyrics files are stored by default in $HOME/lyrics, you can change this by editing the script.

## Dependencies

* You need to have a functionnal **cmus** installation. Head to https://cmus.github.io/ for installation.
* **glyrc**: https://github.com/sahib/glyr

## Installation

Download the script and put it in your path, don't forget making it executable. I suggest the following:

```bash
cd /path/to/install
git clone https://github.com/Navds/cmus-lyrics.git
cd cmus-lyrics
sudo chmod +x lyrics
ln -s $(pwd)/lyrics -t ~/bin
```

## Use

Just enter the command *lyrics* on the terminal and have fun.

```bash
lyrics
```
