![loadbalances](https://github.com/richard-1257/alx-system_engineering-devops/assets/83041703/a7987161-ca65-4a56-9b0b-3285c662bc0f)

# Load balancer

In this project, I continued to build up the configuration of the web server issued in project 0x0B. I was issued two additional servers, one to replicate the Nginx configuration of my original server, and another to set up an HAproxy load balancer on to manage both web servers.

## Tasks 📃
- 0. Double the number of webservers
  - [0-custom_http_response_header](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0F-load_balancer/0-custom_http_response_header): Bash script that installs and configures Nginx on a server with a custom HTTP response header.
    - The name of the HTTP header is `X-Served-By.`
    - The value of the HTTP header is the hostname of the server. 

- 1. Install your load balancer
  - [1-install_load_balancer](https://github.com/richard-1257/alx-system_engineering-devops/blob/master/0x0F-load_balancer/1-install_load_balancer): Bash script that installs and configures HAproxy version 1.5 on a server.
    - Enables management via the init script.
    - Requests are distributed using a round-robin algorithm. 
