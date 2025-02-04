When plex prompts you yo be updated you have to:

- stop the docker compose: `sudo docker compose down`
- update the image: `sudo docker pull lscr.io/linuxserver/plex:latest`
- relaunch the docker compose: `docker compose up -d`
