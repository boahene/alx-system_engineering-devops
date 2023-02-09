*THE FOLLOWING CODES SHOWS WHAT EACH SCRIPTS DOES*

0. Create a script that switches the current user to the user betty. #!/bin/bash su be   tty
1. Script that prints the effective username of the current user. #!/bin/bash whoami
2. Prints all the groups the current user is part of. #!/bin/bash groups
3. Script that changes the owner of the file hello to the user betty. #!/bin/bash chow   n betty hello
4. Create an empty file called hello. #!/bin/bash touch hello
5. Script that adds execute permission to the owner of the file hello #!/bin/bash chmo   d u+x hello
6. script that adds execute permission to the owner and the group owner, and read perm   ission to other users, to the file hello. #!/bin/bash chmod 774 hello
