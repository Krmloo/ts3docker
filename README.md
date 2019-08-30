# ts3docker
docker-compose.yml for fast ts3 server deployment with healthchecks and autorecovery

- Clone this repo
  - `git clone https://github.com/krmloo/ts3docker`
- Enter its directory
  - `cd ts3docker`
- Start server
  - `docker-compose up -d`
- And look up serverquery password & serveradmin token
  - `docker-compose logs -f` (Ctrl+C to detach)
