
![WEB-SERVER](https://user-images.githubusercontent.com/83041703/235007606-3e0408fe-9715-49be-b03e-562731095945.png)

# Web server

In this project, I learned how web servers work and began using one. I was provided a personal server by ALX. I learned how to use scp and Fabric to transfer files to my server. Additionally, I completed a basic configuration of the server using Nginx.


## Tasks 📃
- 0. Transfer a file to your server
     - [0-transfer_file](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0C-web_server/0-transfer_file): Bash script that transfers a file from Holberton's client to a server.
     - Accepts four arguments:
       - The path of the file to be transferred.
       - The IP of the server to transfer the file to.
       - The username that `scp` connects with.
       - The path of the SSH privtae key that `scp` uses.
     - `scp` transfers the file to the user home directory `~/`. 
     
- 1. Install nginx web server
     - [1-install_nginx_web_server](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0C-web_server/1-install_nginx_web_server): Bash script that configures a new Ubuntu machine with Nginx.
     - Nginx listens on port 80.
     - When querying Nginx at its root `/` with a `curl` GET request, it returns a page containing the string `Hello World`.
     
- 2. Setup a domain name
     - [2-setup_a_domain_name](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0C-web_server/2-setup_a_domain_name): A text file containing the domain name set up for the server through [TECH domains](https://get.tech/)

- 3. Redirection
     TO BE COMPLETED 
