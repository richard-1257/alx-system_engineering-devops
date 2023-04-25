

# SSH

In this project, I became familiar connecting to and working with servers using the SSH protocol. I worked on a server provided by ALX.


## Tasks 📃
- 0. Use a private key
     - [0-create_a_file.pp](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0A-configuration_management/0-create_a_file.pp):  Puppet manifest file that creates a file school in the /tmp directory.
       - File permissions: `0744`.
       - File group: `www-data`.
       - File owner: `www-data`.
       - File content: `I love Puppet`.
     
- 1. Install a package
     - [1-install_a_package.pp](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0A-configuration_management/1-install_a_package.pp): Puppet manifest file that install `flask` from pip3.
     
- 2. Execute a command
     - [2-execute_a_command.pp](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0A-configuration_management/2-execute_a_command.pp): Puppet manifest file that kills the process `killmenow`.
