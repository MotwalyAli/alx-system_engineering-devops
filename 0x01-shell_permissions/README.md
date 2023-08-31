                                   
                                     Permission Commands README file

Note: The <> is used here to contain the text and and is not a part of the script itself




chmod	-> we use this command to make a file executable. 

sudo	-> we use in with other superuser commands in order to give us permission to e.g. change a file or a directory owner {sudo chown <newuser-name> <file or dir-name> }.

su	-> this command allow you to switch the user account to another one {su <username>}.

chown	-> this command is used to change the owner of a file or directory {chown <file or dir-name> <owner-name>}.

chgrp	-> this command will change the group ownership of a file or dir {chgrp <group-name> <file-name>}

id	-> we can use this command to display  the user ID and group ID for the current user.

groups	-> this command is used to know which group the current user belong to.

whoami	-> this command used to display the username of the current user.

adduser	-> this command allow you to create a new user and allow you to inter the information of it.

useradd -> we use this command to create a new user but it requires more options in the command itself for example {useradd -m -s /bin/bash newuser}.

addgroup-> this command will allow you to create a new group with more options e.g. {addgroup <group-name>}

