# Docker contained nginx reverse proxy

Quick docker example of an nginx reverse proxy for a local network (not just for the network used by the compose)

See ``/nginx/etc/nginx/conf.d/`` and ``/docker-compose.yml`` for the nginx config example.

In this case ``http://reverse1.localhost`` serve the ``web1`` container and ``http://reverse2.localhost`` serve the ``web2`` container.