# Bastion

- a raspberry pi has a service running on port 3000
- it creates a revers SSH tunnel with the bastion: `ssh -NTR 8081:localhost:3000 tb@bastion.tb.io`
- traefik forwards traffik for a given domain to the port
