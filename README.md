# EzCode
a simple script engine based off of python, made for top simplicity.
But How Do You Even Install EzCode?
# Installation process (windows only)
*step 1*: install python (REQUIRED DEPENDENCY), you can install python from the official website or the microsoft store (reccomended version: 3.13.x since 3.14.x is not supported yet)

*step 2*: install pygame (ALSO A REQUIRED DEPENDENCY), you can install pygame by: downloading python, opening powershell and type in ||pip install pygame||

*step 3*: download the .zip file from the releases tab, please install the latest versions for the best experience

*step 4*: extract it directly on your C: drive, important note: here's how the directory should look like "C:\EzCode\main files\Examples4EzCode\secondary examples"

*step 5*: this is a very important step, open the main directory, then the Examples4EzCode folder, from there right click any of the ".ez" files and click open with, choose "browse app on this computer" and go to the directory "C:\EzCode\" there you should double click "launcher.bat". That is the file you need to open, that will open a CMD window which will then show you a window for your script execution

*step 6* (optional): download the testing files for EzCode from the releases tab and open all the files, one by one to see if your installation was correct.

but how do you even use EzCode,

# Usage

EzCode is designed for top simplicity, so while making it i say, hmm why not just make 1 command the most powerful one?

*set* is the most important command in the entirety of the engine, before we get there, let's start from the top and easy

*Text Interface Format*

how to use the text interface format?

at the start of each script in EzCode you have to set the format (that is due to an unfixable bug), to set a text interface format start the script by writing "Text", after that you jump a line or 2, and write "loop-loopname" to start a loop, and doing "loop-loopname-end" ends the loop, anything before the loop is considered setup. To display any text you have to write  "say ("specified text")"  

An example of a text script is:

|||||||||||||||||||||||||

Text

loop-Hello

say ("Hello, World!")

loop-Hello-end

||||||||||||||||||||||||

The EzCode contruibuters have realised that this might be too many lines, but this format truely simplifies more complex projects, especially graphical interface format files

*Graphical Interface Format*

The Graphical Interface Format was the first format made for EzCode, but how does it work? and more importantly how to use it?

at the start of each script in EzCode you have to set the format (that is due to an unfixable bug), to set a text interface format start the script by writing "Grid(x, y)", after that you jump a line or 2, and write "loop-loopname" to start a loop, anything before the loop is considered setup. main function of graphical interface formats is the set grid command, to set a grid to a specific color there's a hardcoded color pallete (currently no RGB custom or hex support) to set a specific grid to a color we use the set command by writing "set (Grid[r𝑥, c𝑦] {colorcode})" the neat part is that you can set a specific 1x1 image in a grid slot instead for a hardcoded color system, how do you use it? well it's very simple, just write "set (Grid[r𝑥, c𝑦] {"image directory"})

here's the color code system:

"0" is black

"1" is red 

"2" is orange 

"3" is yellow 

"4" is lime 

"5" is green 

"6" is dark green 

"7" is light blue 

"8" is cyan 

"9" is blue 

"10" is dark blue 

"11" is magenta 

"12" is purple 

"13" is dark pink 

"14" is pink 

"15"-light pink 

"16"-dark gray 

"15" is gray 

"16" is light gray 

"17" is white

another fact about the graphical interface format is that it's possible to fill squares with a specific color (doesn't work for images yet) by writing "set (Grid[r𝑥1, c𝑦1, r𝑥2, c𝑦2])"

the best example of use utilises all of the graphical interface format functions:

|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||

Grid(16, 16)

loop-loop

set (Grid[r1, c1, r16, c16] {5})

set (Grid[r6, c6] {"(C:)\users\TheNewExtremeRay\Documents\image.png"})

set (Grid[r5, c6] {1}).

loop-loop-end

|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
