
# Basic 'Find File' Commands
--------------------------
find / -name foo.txt -type f -print             # full command </br>
find / -name foo.txt -type f                    # -print isn't necessary </br>
find / -name foo.txt                            # don't have to specify "type==file" </br>
find . -name foo.txt                            # search under the current dir </br>
find . -name "foo.*"                            # wildcard </br>
find . -name "*.txt"                            # wildcard </br>
find /users/al -name Cookbook -type d           # search '/users/al' </br>
