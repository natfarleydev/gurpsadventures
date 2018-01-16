# gurpsadventures
Repository for home made GURPS adventures

## Requirements
These adventures require the custom `gurps` latex package found
[here](https://www.github.com/nasfarley88/gurps-latex-package). To install,
simply download the package with git and install it:

    git clone https://www.github.com/nasfarley88/gurps-latex-package
    cd gurps-latex-package/source
    make inst

Note that it requires the use of LuaLaTeX.

## Making the projects
To make all the projects:

    make
    
(or for a faster compile time

    make -j4
    
where 4 is the number of cores.)
