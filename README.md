# ts3docker
Just a docker-compose.yml for fast ts3 server deployment

- Clone this repo
  - `git clone https://github.com/Krmloo/ts3docker`
- Enter its directory
  - `cd ts3docker`
- Create new volume (or use pre-existing one) for database storage
  - `docker volume create --name=ts3db`
- Create new volume (or use pre-existing one) for file storage
  - `docker volume create --name=ts3files`
- Start it
  - `docker-compose up -d`
- And look up serverquery password & serveradmin token
  - `docker-compose logs -f` (Ctrl+C to detach)
