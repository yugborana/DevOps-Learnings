# Streams and Files
- Standard Streams-
  - 1. `stdin` (Standard Input)   Code:0
  - 2. `stdout`(Standard Output)  Code:1
  - 3. `stderr`(Standrad Error)   Code:2
  
- Streams are used to transfer data, takes input and gives output.
    - output can be in terminal.
    - in some file.
    - or in pipe which redirects it.
    - If you want to redirect, `>` is used. Eg : `ls > output.txt` command overwrites the data.
    - To append the data, `ls >> output.txt` is used.

- `stderr`
  - Now the lg > output.txt command gives an error, to tackle this lg 2> output.txt is used because error is denoted by 2.
  - `lg 2> /dev/null` --> To nullify error.

- `less`
  - Opens output in seperate window. Eg: `less /var/log/syslog`
  - To view large files without populating your terminal. Do `ls -la /etc | less` to close the seperate window press "q".
 
- `pipe`
  - Takes standard output of one command and feeds it to the next command as standard input.

- Environment Variables `env`
  - It store and provide useful information that shells and processes can use.
  - `$PWD`  - gives present working directory. Maintains a present working directory.
  - `$PATH` - contains all the path that your pc will search whenever you enter a command.  
  > Everything in linux is a file even the commands.

## Some Commands
- `head` --> Prints first 10 lines of a file. Eg: `head output.txt`
  - `head -n 15 output.txt` : Prints first 15 lines of a file.

- `tail` --> Prints last 10 lines of a file. Eg: `tail output.txt`
  - `tail -n 15 output.txt` : Prints last 15 lines of a file.

- `sort` --> It gives sorted version of the file. Eg: `sort testing.txt`
  - `sort -r testing.txt` : It is for reverse sorting.

- `translate` --> To change format of letters in a file.
  - `cat testing.txt | tr a-z A-Z` : Letters from lowercase to uppercase.

- `uniq` --> Line utility that reports or filters out the repeated lines in a file. Eg: `uniq testing.txt`
  - `uniq -c testing.txt` : It tells how many times a line was repeated by displaying a number as a prefix with the line.
  > Drawback: The above command only works when the duplicate words are next to each other. 
  > To overcome it, firstly sort the file and then `sort testing.txt | uniq`

  - `uniq -u testing.txt` : It allows you to print only unique lines.
  - `uniq -d testing.txt` : It only prints the repeated lines and not the lines which aren’t repeated.

- `wc` (Word Count) Eg: `wc testing.txt`
  - `wc -l testing.txt` : Prints the number of lines present in a file.
  - `wc -w testing.txt` : Prints the number of words present in a file.
  - `wc -c testing.txt` : Displays count of bytes present in a file.
 
- `grep` 
  -  Searches a file for a particular pattern of characters, and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression (grep stands for global search for regular expression and print out). 
  -  Eg: `env | grep PWD`
