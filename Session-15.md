# Search and Filter utility in Linux-
Search utilities are used to search files from the system where as filter utilities filters the 
output. Following are some filter tools that can we use:

## sort –
- Sorts the lines alphabetically by default but there are many options available to modify the sorting mechanism.
- sort filename
#### options-
- -r: Reverse the sort order
- -n: Sort numerically
- -o: Output the result to a file

## uniq –
- Removes duplicate lines. uniq has a limitation that it can only remove continuous duplicate lines.
- uniq filename
#### options-
- -d: Only print duplicate lines
- -u: Only print unique lines

## sed – 
- sed stands for stream editor.
- It allows us to apply search and replace operation on our data effectively.
#### options:
* s: substitute occurrence of a pattern with a replacement
- sed 's/old/new/' filename
* p: Print the lines that match a pattern.
- sed -n '/pattern/p' filename
* -i: Edit the file in place (i.e., modify the original file)
- sed -i 's/old/new/' filename
* d: Delete lines that match a pattern
  -sed '/pattern/d' filename.
## wc –
- wc command gives the number of lines, words and characters in the data.
#### Options:
- -l Show Line Count
- -w Display word count
- -m Show character count
## grep – 
- grep is used to search a particular information from a text file.
- grep 'pattern' filename

#### Options:
- -v Invert match.
- -c Output count of matching lines only.
## locate – 
- The locate command is used to find files by their filename. 
- The locate command is lightning fast because there is a background process that runs on your system that continuously finds new files and stores them in a database.
- When you use the locate command, it then searches that database for the filename instead of searching your filesystem. 
#### Options:
- -i Ignore uppercase vs. lowercase.
- -c Output count of matching lines only.
- -l Limiting search result
## find –
- Find command is used to search and locate the list of files and directories based on conditions you specify for files that match the arguments.
- Find can be used in a variety of conditions like you can find files by permissions, users, groups, file type, date, size, and other possible criteria.
- Syntax:
#### find <search_path> <options> <required-parameters>
##### Options,
- -name <file_name> Search for a file with the specified name
- -perm <mode> File's permission bits are exactly mode (octal or symbolic)
- -size <N/+N/-N> Find files with specific size (size > or size <)
- -user <name> File is owned by user specified
- -uid <uid> Files numeric user id is the same as uid
- -group <grp_name> File is owned by group specified
- -gid <gid> The file belongs to group with the ID n




