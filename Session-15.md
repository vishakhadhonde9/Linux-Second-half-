# Search and Filter utility in Linux-
Search utilities are used to search files from the system where as filter utilities filters the 
output. Following are some filter tools that can we use:

## cat – 
displays the text from file as output.
## head – 
display top few lines (defaults ten lines) of output
## tail – 
displays bottom few lines (defaults ten lines) of output
## sort –
Sorts the lines alphabetically by default but there are many options available to modify the sorting mechanism.
## uniq –
Removes duplicate lines. uniq has a limitation that it can only remove continuous duplicate lines.
## sed – 
- sed stands for stream editor. It allows us to apply search and replace operation on our data effectively. 
- sed is quite an advanced filter and all its options can be seen on its man page
## wc –
wc command gives the number of lines, words and characters in the data.
#### Options:
-l Show Line Count
-w Display word count
-m Show character count
## grep – 
- grep is used to search a particular information from a text file.
#### Options:
- -i Ignore uppercase vs. lowercase.
- -v Invert match.
- -c Output count ofmatching lines only.
- -n Precede each matching line with a line number.
## locate – 
- The locate command is used to find files by their filename. 
- The locate command is lightning fast because there is a background process that runs on your system that continuously finds new files and stores them in a database.
- When you use the locate command, it then searches that database for the filename instead of searching your filesystem while you wait. 
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




