# How to Change Permissions in Linux-
- The command you use to change the security permissions on files is called “chmod“, which stands for “change mode".
### Syntax-
* chmod <u,g,o><+,-,=><r,w,x> <file_name>
# Octal Notation Method-
### Syntax- 
* chmod <permission_in_numbers> <file_name>

| Octal | Binary | Permission                |
|-------|--------|---------------------------|
| 0     | 000    | No permission (---)      |
| 1     | 001    | Execute (--x)             |
| 2     | 010    | Write (-w-)               |
| 3     | 011    | Write and execute (-wx)   |
| 4     | 100    | Read (r--)                |
| 5     | 101    | Read and execute (r-x)    |
| 6     | 110    | Read and write (rw-)      |
| 7     | 111    | Read, write, and execute (rwx) |


* chmod <permission_in_numbers> <file_name>
