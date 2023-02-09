l#!/bin/bash
chmod -R +X .*THE FOLLOWING CODES SHOWS WHAT EACH SCRIPTS DOES*

0. Create a scriphat switches the current user to the user betty. #!/bin/bash su be   tty

1. Script that prints the effective username of the current user. #!/bin/bash whoami

2. Prints all the groups the current user is part of. #!/bin/bash groups

3. Script that ches the owner of the file hello to the user betty. #!/bin/bash chown betty hello

4. Create an empty file called hello. #!/bin/bash touch hello

5. Script that adds execute permission to the owner of the file hello #!/bin/bash chmod u+x hello

6. script that adds execute permission to the owner and the group  #!/bin/bash chmod ug+x,o+r hello

7. script that adds execution permission to the owner, the group owner and the other users, to the file hello #!/bin/bash chmod ugo+x hello

8. script that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
#!/bin/bash chmod 007 hello

9. Script that sets the mode of the file hello to this "-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello" #!/bin/bash chmod 753 hello

10. Script that sets the mode of the file hello the same as olleh’s mode. #!/bin/bash/chmod --reference=olleh hello

11. Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. #!/bin/bash chmod -R +X .

12 .Create a script that creates a directory called my_dir with permissions 751 in the working directory. #!/bin/bash mkdir -m 751 my_dir

13. script that changes the group owner to school for the file hello #!/bin/bash chgrp school hello

14. script that changes the owner and the group owner of _hello to vincent and staff respectively  #!/bin/bash chown vincent:staff *

15. changes the owner and the group owner of _hello to vincent and staff respectively. #!/bin/bash chown -h vincent:staff _hello

16.changes the owner of the file hello to betty only if it is owned by the user guillaume. #!/bin/bash chown --from=guillaume betty hello

17. Write a script that will play the StarWars IV episode in the terminal. #!/bin/bash telnet towel.blinkenlights.nl