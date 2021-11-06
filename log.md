- `echo $SHELL`
- `echo $HOME` == `pwd` (if in home dir)
- `clear` to clear terminal 
- `ls -l` (`-l` means _long_)
- `ls -l Desktop/` (`/` optional, to show specific dir)
- `ls -l Desktop/example.csv` to show specific file
- `ls -ld Desktop/` to show permissions - result would be `drwxr-xr-x 3...` where `d` is `directory`, `rwx` is `read, write & execute` for the user (me/you);  the second batch `r-x` is `read, execute` for a group, and then `r-x` is `read, execute` for anyone.
- `ls -l -a` to show all files, including hidden files that start with `.`
- `ls -l .` to show root
- `ls -l ..` to show one dir above
- `cd` on its own sends you to your home dir
- ```the "bit positions" are:
    User | Group | World
    111  =   7   = rwx
    101  =   5   = r_x
    ```
- `cp <PATH TO FILE OR DIR> .` copies file or dir into current dir
- `rmdir` removes directory