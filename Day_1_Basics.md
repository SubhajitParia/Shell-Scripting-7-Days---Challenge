#!/bin/bash




echo "This is shell scripting day 1 challenge"



#Task 2: Variables

variable1="Hello"
variable2="Bash"

# Task 3: Using Variables

greeting="$variable1, $variable2"

echo "$greeting Welcome to the world of Bash Scripting"


# Task  5: Using Built-in Variables
echo "My current bash path - $BASH"
echo "Bash version I am using - $BASH_VERSION"
echo "PID of bash I am running - $$"
echo "My home directory - $HOME"
echo "Where am I currently? - $PWD"
echo "My hostname - $HOSTNAME"


# Task  6: Wildcards
echo "Files with .txt extension in the current directory:"
ls *.sh

