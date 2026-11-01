
This is a ready to go deployment of Garage with a Web UI designed to work with Traefik as a reverse proxy. See my [Traefik](https://github.com/UntouchedWagons/WorkingTraefikExamples) guide for more info on that.

The provided `compose.yaml` will get everything started but once Garage has set up the single node cluster remove the `command` line noted in the compose file and re-run `docker compose up -d`.
