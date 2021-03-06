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
- `rm -rf dirname` force removes a dir
- grep structure to search/find patterns in files:

            command pattern file
example:    `grep`  `the`   `file.csv`

- grep command to ignore pattern:   `grep -v the <file>` 
- `grep -r boisterious *` searches recursively __everywhere__
- `find . -name <file>` finds directory of a file
- `sudo` stands for `super user do`
- `2>/dev/null` is used to discard and suppress error outputs