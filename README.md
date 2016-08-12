# Basic nginx authentication

This container allows to publish a website using nginx and restrict the access using the authentication module of nginx.

You can also:
  - Change index.html as you want
  - Create new users to login
  - Change basic configuration of nginx

# Run

To run the built image from docker hub use:
> $ docker run -d -p 80:80 xavijs/nginx-basic-auth

Or if you have the sources and you want to run using docker-compose then in the root of the project:
> $ docker-compose up -d


This will start the server in port 80, you can access by clicking [HERE](http://localhost) and you can modify all files under "/www/" folder and see changes in web without rebuilding docker.

# Default login

By default this container is using this login.

User: hello
Pass: world


