# ansible-role

The role contains adding a user with a specific uid and gid. In the case of an existing user with this uid and gid, it will be changed to the specified other. Also, for the new user, an ssh-key is added, autorun, execution of commands without a sudo password.