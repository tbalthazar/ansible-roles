# PiHole Role

## Config Vars

- hostname
- users

- pihole_install_dir
- pihole_domain
- pihole_docker_image
- pihole_default_group_id
- pihole_default_group_name
- pihole_default_user_id
- pihole_default_user_name
- pihole_web_password

## Notes

PiHole is not proxied behind Traefik cause I didn't find a way to forward the client IP, meaning all the DNS queries appear to come from Traefik itself. I tried to set the `forwardedHeaders` in Traefik but it didn't help

Some links related to the issue:
- https://discourse.pi-hole.net/t/traefik-and-pihole-with-docker-forward-client-ip/45088/7
- https://community.traefik.io/t/use-x-forwarded-in-traefik-v2/5206
