
# basic 'find file' commands
--------------------------
[x] find / -name foo.txt -type f -print             # full command
[x] find / -name foo.txt -type f                    # -print isn't necessary
[x] find / -name foo.txt                            # don't have to specify "type==file"
[x] find . -name foo.txt                            # search under the current dir
[x] find . -name "foo.*"                            # wildcard
[x] find . -name "*.txt"                            # wildcard
[x] find /users/al -name Cookbook -type d           # search '/users/al'
