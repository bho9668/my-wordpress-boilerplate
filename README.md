# My Wordpress Boilerplate

Docker project to quickly and easily launch a wordpress website with:
- Latest Wordpress running on
- MariaDB, with
- phpMyAdmin, all handled with
- Traefik (including dashboard)

Tested on Ubuntu 18.04 Server.

## Installation

Edit the sample.env file with your desired usernames, passwords and domains. 

[Optional]
Edit the docker-compose file and replace `my_application` with whatever you want.

Upload the whole directory anywhere on your server, make sure you have docker and docker-compose installed, and then run:

`docker-compose up -d`