# Christmas Card
The christmas card can be compiled with PdfLaTeX. It is the default compiler for the most LaTeX distributions and, as a consequence, people do not have to switch the compiler in order to compile this card.

## Adding a name
It is possible to add a name after the "Merry Christmas". This can be done by specifying a name in the empty curly braces where it says `\newcommand{\name}{}`.
Depending on the length of the name, the vspaces before and after the texts may need to be adjusted. 

## Font
Due to the usage of PdfLaTeX, the variety of fonts that can be used is highly limited. There is one alternative font included in the code. Follow the instructions in the code in order to switch the font. Also, don't forget to comment out the `\bbfamily` command if you want to use the alternative font.
More fonts can be found at the [tug.org page](https://tug.org/FontCatalogue/). Some of them require additional packages or the usage of XeLaTex or LuaLaTeX.


test
