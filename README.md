copyright 2025 - the future
this is a full description of the lang: C@
this is a lang that plans to make it easier for new devs/coders to get a basic understanding of programming/coding and for devs just to try out and give me suggestions on what i should add/change
--------------------
1- how to use:
run ./CAtrunner
write the code
after each line hit enter
write "srt" to interpret & run
or "exit" to exit
--------------------
2-syntax:
containers () {} [] <> "" '' cant be multiple lines, only one
'&' acts as a semicolon 
eg usage:
add x = 8 & show x
---------------------
3- keywords & uses:
-show <text>: shows a text or expression, the delimiter i decided to use is #
  eg usage: 
show "hello " # "world!"
show 6 + 8 - 6 * 3
show "x" # " = " # x

-add <name> = <value>: a type declaration word,it supports strings and numbers 
  eg usage:
add x = 2
add y = 7 - 16
add z = " hello"

-bool <var> = <true/false>: basic boolean values
  eg usage:
bool x = true
bool y = false

-mirr <boolean>: change the boolean value from true to false or false to true
  eg usage:
bool x = true
mirr x
show x # "this will be: false"

-arr <name> <size> <array>: a basic array declarer
  eg usage:
arr x 5 "1,2,3,4,5"
show x # "this will be 12345"

-func <name> [code]: a basic function system with no arguments
  eg usage:
func hi [show "hi"]

-macro <name> <args> [code]: a macro system with arguments 
  eg usage:
macro greet (x) (y) [show x # " says hi " # y]
greet "he" "her"

-date : shows current date 

-cls : clears the screen 

-ask <var> : sets a var to input 
  eg usage:
ask x
ask y
show x + y

-getPress <var> : like ask but instant (like _getch() in cpp)
  eg usage:
getPress x
show x + 1

-makeFile <name> <content>: makes a file
  eg usage:
makeFile hi.txt hello world!

-execFile <name>: executes a file
  eg usage:
execFile hello_world.cca

-showDir <directory>: shows all files/folders in a directory
  eg usage:
showDir myDirectory

-CurrentPath: shows the path of the file

-run <code>: runs a code
  eg usage:
show "enter code: "
ask x
run x

-terminal (code): runs a code in the terminal
  eg usage:
terminal (clear)

-set <name> = <value>: changes the value of a var
  eg usage:
set x = x + 1

-CopyFile <file> <file>: copies a file
  eg usage:
CopyFile myfile.txt mysecFile.txt

-MoveFile <file> <file>: moves a file
  eg usage:
MoveFile myFile.txt ~/myFolder/myFile.txt

-wait <time> [code] : waits for a selected time (seconds) then executes a code
  eg usage:
wait 7 [show "this shows at the start!"]
show "you waited 7 secs!"

-nydebug: shows a full on debug list

IFs AND ELIFs AND ELSE ARE VALID CODE, BUT THEY DON'T DO ANYTHING FOR NOW

-read <file>: doesn't do anything, just makes sure a file exists 
  eg usage:
read myFile.txt

-random <min> <max>: shows a random num from min to max

-showFile <file>: shows a file's content

-round/ceil/floor <num>: shows a rounded version of that num

-roundVar/ceilVar/floorVar <var> :sets a variable to rounded version of it

-repeat <count> [code]: repeats a block of code a specified amount of time
  eg usage:
repeat 57 [show "hi"]

-repVar <var> [code]: like repeat but repeats the code the value of the variable times

-join <var1> <var2> "delimiter": joins two strings or arra6or strings and arrays, 
WARNING: THE DELIMITER CANNOT BE EMPTY OR SET TO ""

-infloop [code] :does a line of code for a specific amount of time, at lighspeed

-deleteFile <file> : deletes a file

ALL OTHER THINGS ARE INCOMPLETE
-------------------------------
