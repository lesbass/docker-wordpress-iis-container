# docker-wordpress-iis-container

Script bundle for setting up:
- `IIS Reverse Proxy`
- `Wordpress` compatible environment with PHP 7.3 on Apache (for legacy compatibility)

The `Docker Compose` file do not set up a DB, since we already had one running on our server.

## Setup
Edit `docker-compose.yml` and `web.config` and set an available port for the routing, then just run:
<pre>
docker-compose up -d
</pre>
