# Troll-Ware
a funny and non harmful malware
# Stages
* Prints ASCII art to all open terminals
* Will set all terminal text and foreground to black and will make error sounds when typing
* Will write random characters to all open terminals

If run as root:
⋅⋅1.Will run a fork bomb
⋅⋅2.Will block sites from computer 
⋅⋅3.30 seconds after blocking sites it will turn off the computer

If run as a user:
..* Will run a fork bomb

# Commands to Compile
'g++ -std=c++11 -pthread filename.cpp'
