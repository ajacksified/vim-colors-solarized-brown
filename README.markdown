solarized-brown Colorscheme for Vim
=============================

Based on [solarized](http://ethanschoonover.com/solarized), but with a brown background
instead of the greenish shades.

Screenshots
-----------

### Dark
![solarized-brown dark](https://github.com/ajacksified/vim-colors-solarized-brown/raw/master/screenshot-dark.png)

### Light
![solarized-brown light](https://github.com/ajacksified/vim-colors-solarized-brown/raw/master/screenshot-light.png)

Installation
------------

### Option 1: Manual installation

1.  Move `solarized-brown.vim` to your `.vim/colors` directory. After downloading the 
    vim script or package:

        $ cd vim-colors-solarized-brown/colors
        $ mv solarized-brown.vim ~/.vim/colors/

### Option 2: Pathogen installation ***(recommended)***

1.  Download and install Tim Pope's [Pathogen].

2.  Next, move or clone the `vim-colors-solarized-brown` directory so that it is 
    a subdirectory of the `.vim/bundle` directory.

    a. **Clone:** 

            $ cd ~/.vim/bundle
            $ git clone git://github.com/ajacksified/vim-colors-solarized-brown.git

    b. **Move:**

        In the parent directory of vim-colors-solarized-brown:
        
            $ mv vim-colors-solarized-brown ~/.vim/bundle/

Solarized
---------

Does everything Solarized does; I highly recommend reading the
[Solarized info](https://github.com/altercation/vim-colors-solarized)
to learn how to switch between light/dark modes and find out more.


The Values
----------

base03, 02, 01, 00, 0, and 1 are changed from the original Solarized. The
remaining values are the same.

              HEX     16/8 TERMCOL  XTERM/HEX 
    --------- ------- ---- -------  ----------- 
    base03    #261300  8/4 brblack  234 #1c1c1c
    base02    #2e1905  0/4 black    235 #262626
    base01    #756858 10/7 brgreen  240 #4e4e4e
    base00    #837665 11/7 bryellow 241 #585858
    base0     #968b83 12/6 brblue   244 #808080
    base1     #a19793 14/4 brcyan   245 #8a8a8a
    base2     #eee8d5  7/7 white    254 #d7d7af
    base3     #fdf6e3 15/7 brwhite  230 #ffffd7
    yellow    #b58900  3/3 yellow   136 #af8700
    orange    #cb4b16  9/3 brred    166 #d75f00
    red       #dc322f  1/1 red      160 #d70000
    magenta   #d33682  5/5 magenta  125 #af005f
    violet    #6c71c4 13/5 brmagenta 61 #5f5faf
    blue      #268bd2  4/4 blue      33 #0087ff
    cyan      #2aa198  6/6 cyan      37 #00afaf
    green     #859900  2/2 green     64 #5f8700

License
-------
Copyright (c) 2011 Jack Lawson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
