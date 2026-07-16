# DAY-3
Linux File Management, Redirection and Bash Scripting

## Date
03 July 2026
### Objective
The objective of Day 3 was to gain practical knowledge of Linux command-line operations, text processing, file compression techniques, Bash scripting fundamentals and advanced shell features. The session focused on improving command-line productivity through redirection, pipes, wildcards and text-processing tools.
### Topics Covered
#### 1. Redirection in Linux
Redirection is used to change the default input or output of Linux commands. Instead of displaying output on the terminal, it can be stored in a file or read from a file.
##### Types of Redirection
- `>` Output Redirection
- `>>` Append Redirection
- `<` Input Redirection
##### Commands Practiced
```bash
echo "Hello Linux" > file.txt
echo "Welcome" >> file.txt
cat < file.txt
```
##### Learning Outcomes
- Saving command output into files.
- Appending data without deleting previous contents.
- Reading input from files.
#### 2. Pipes (`|`)
A Pipe connects two or more Linux commands. The output of one command becomes the input of another command.
##### Commands Practiced
```bash
echo "Hello Linux" | cat
ls | cat
```
##### Learning Outcomes
- Combining multiple commands.
- Processing command output efficiently.
- Understanding command chaining.
#### 3. Wildcards
Wildcards are special characters used to search and manage multiple files.
##### Wildcards Learned
- `*` → Zero or more characters
- `?` → Exactly one character
- `[ ]` → Matches characters from a specified set or range
##### Commands Practiced
```bash
ls *.txt
ls file?.txt
ls file[12].txt
```
##### Learning Outcomes
- Searching multiple files.
- Managing groups of files.
- Faster file operations.
#### 4. Quoting
Quoting allows text containing spaces or special characters to be treated as a single string.
###### Types
- Single Quotes (`' '`)
- Double Quotes (`" "`)
##### Commands Practiced
```bash
echo "Hello Linux"
echo 'Hello Linux'
touch "my file.txt"
```
##### Learning Outcomes
- Handling filenames with spaces.
- Understanding single and double quotes.
- Protecting special characters.
#### 5. Escaping Characters
Escaping characters allows special symbols to be treated as ordinary text by using the backslash (`\`).
##### Commands Practiced
```bash
touch my\ file.txt
echo \$100
echo \"Linux\"
```
##### Learning Outcomes
- Working with filenames containing spaces.
- Printing special characters.
- Understanding the escape character (`\`).
#### 6. Text Processing Tools
Linux provides powerful tools for searching, filtering and editing text.
##### Commands Learned
###### grep
Searches for specific words or patterns.
```bash
grep "Linux" notes.txt
```
###### awk
Processes data field by field.
```bash
awk '{print $1}' data.txt
```
###### sed
Edits and replaces text.
```bash
sed 's/Linux/Ubuntu/' file.txt
```
##### Learning Outcomes
- Searching text.
- Extracting data.
- Editing files without opening them.
#### 7. File Compression
Linux provides utilities for compressing files and creating archives.
##### Commands Learned
###### tar
```bash
tar -cvf backup.tar Documents/
```
###### gzip
```bash
gzip file.txt
```
###### zip
```bash
zip project.zip file1.txt file2.txt
```
###### gunzip
```bash
gunzip file.txt.gz
```
##### Learning Outcomes
- Creating archive files.
- Compressing files.
- Decompressing compressed files.
- Saving storage space.
#### 8. Bash Scripting
An introduction to Bash scripting was provided.
##### Topics Covered
- What is Bash
- What is Shell
- Importance of Shell Scripts
- Basic structure of a Bash script
- Running shell scripts
- File permissions for scripts
###### Sample Script
```bash
#!/bin/bash
echo "Hello Linux"
```
###### Learning Outcomes
- Understanding Bash scripting basics.
- Executing shell scripts.
- Automating simple tasks.
#### 9. Linux Help Commands
Learned how to obtain information about Linux commands.
###### Commands
```bash
man ls
help cd
whereis cat
whatis cat
```
###### Learning Outcomes
- Accessing Linux documentation.
- Understanding command usage.
- Finding executable locations
#### Practical Activities Performed
- Practiced Redirection commands.
- Used Pipe operator.
- Worked with Wildcards.
- Performed Quoting and Escaping.
- Executed text processing commands.
- Learned file compression commands.
- Explored Bash scripting.
- Used Linux help utilities.
#### Learning Outcomes
By the end of Day 3, I learned:
- Linux Redirection techniques.
- Command chaining using Pipes.
- File searching using Wildcards.
- Working with Quoting and Escaping Characters.
- Basic text processing using grep, awk and sed.
- File compression and archiving.
- Bash scripting fundamentals.
- Linux help and documentation commands.
- Efficient Linux command-line operations
