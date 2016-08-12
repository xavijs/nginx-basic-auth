# Basic nginx authentication

This container allows to publish a website using nginx and restrict the access using the authentication module of nginx.

You can also:
  - Change index.html as you want
  - Create new users to login
  - Change basic configuration of nginx

# Run

In the root of the project:
> $ docker-compose up -d

This will start the server in port 80, you can access here: http://localhost and you can modify all files under "/www/" folder and see changes in web without rebuilding docker.
