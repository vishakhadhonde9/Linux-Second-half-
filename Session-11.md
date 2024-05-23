# How to Change Permissions in Linux-
- The command you use to change the security permissions on files is called “chmod“, which stands for “change mode".
### Syntax-
* chmod <u,g,o><+,-,=><r,w,x> <file_name>
# Octal Notation Method-
### Syntax- 
* chmod <permission_in_numbers> <file_name>
| Octal No. | Binary   | Permission |
|-----------|----------|------------|
| 0         | 000      | ---        |
| 1         | 001      | --x        |
| 2         | 010      | -w-        |
| 3         | 011      | -wx        |
| 4         | 100      | r--        |
| 5         | 101      | r-x        |
| 6         | 110      | rw-        |
| 7         | 111      | rwx        |

0 000 ---
1 001 --x
2 010 -w3 011 -wx
4 100 r--
5 101 r-x
6 110 rw7 111 

