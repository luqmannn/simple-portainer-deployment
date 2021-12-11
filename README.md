# Simple Portainer Deployment

1. Clone the repo
2. Copy `docker-compose.yml` file to `/opt/portainer` directory. Create one if there is none.
3. Run `docker-compose up -d` in the directory.

## Troubleshoot error

`ERROR: Couldn't connect to Docker daemon at ....`
- Run the command as `sudo`

`ERROR: Volume declared as external but could not be found`
- Run `docker volume create --name=name_of_the_volume`
