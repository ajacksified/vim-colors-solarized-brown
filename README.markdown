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

L\*a\*b values are canonical (White D65, Reference D50), other values are 
matched in sRGB space.

    solarized-brown HEX     16/8 TERMCOL  XTERM/HEX   L*A*B      sRGB        HSB
    --------- ------- ---- -------  ----------- ---------- ----------- -----------
    base03    #261300  8/4 brblack  234 #1c1c1c 15 -12 -12   0  43  54 193 100  21
    base02    #2e1905  0/4 black    235 #262626 20 -12 -12   7  54  66 192  90  26
    base01    #756858 10/7 brgreen  240 #4e4e4e 45 -07 -07  88 110 117 194  25  46
    base00    #837665 11/7 bryellow 241 #585858 50 -07 -07 101 123 131 195  23  51
    base0     #968b83 12/6 brblue   244 #808080 60 -06 -03 131 148 150 186  13  59
    base1     #a19793 14/4 brcyan   245 #8a8a8a 65 -05 -02 147 161 161 180   9  63
    base2     #eee8d5  7/7 white    254 #d7d7af 92 -00  10 238 232 213  44  11  93
    base3     #fdf6e3 15/7 brwhite  230 #ffffd7 97  00  10 253 246 227  44  10  99
    yellow    #b58900  3/3 yellow   136 #af8700 60  10  65 181 137   0  45 100  71
    orange    #cb4b16  9/3 brred    166 #d75f00 50  50  55 203  75  22  18  89  80
    red       #dc322f  1/1 red      160 #d70000 50  65  45 220  50  47   1  79  86
    magenta   #d33682  5/5 magenta  125 #af005f 50  65 -05 211  54 130 331  74  83
    violet    #6c71c4 13/5 brmagenta 61 #5f5faf 50  15 -45 108 113 196 237  45  77
    blue      #268bd2  4/4 blue      33 #0087ff 55 -10 -45  38 139 210 205  82  82
    cyan      #2aa198  6/6 cyan      37 #00afaf 60 -35 -05  42 161 152 175  74  63
    green     #859900  2/2 green     64 #5f8700 60 -20  65 133 153   0  68 100  60

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
