![application_server](https://github.com/richard-1257/alx-system_engineering-devops/assets/83041703/cd71ade8-3686-494e-99e8-785e0626bbbe)

# Application server
This was the application deployment project for our AirBnB clone. In this project, I configured Nginx on the web servers provided me by ALX to serve a WSGI Flask app running through Gunicorn. Additionally, I set up an Upstart script to keep the application running on server reboots.

## Tasks 📃
- 0. Set up development with Python
    - In this task, I configured the file `web_flask/0-hello_route.py` from my [AirBnB_clone_v2](https://github.com/richard-1257/AirBnB_clone_v2) to serve content on the route `/airbnb-onepage/,` running on port `5000.`

- 1. Set up production with Gunicorn
  - This task involved setting up a production environment, installing and configuring Gunicorn to serve the same file from task 0.
 
- 2. Serve a page with Nginx
