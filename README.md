# dockerserver
One command install script for debian based systems after OS installation. Standard install includes Docker, Docker Compose and Dockge, a webui for managing docker compose

Also includes one command install scripts for popular docker containers.

Ubuntu Server is great for beginners.


# Command
`curl -fsSL https://raw.githubusercontent.com/alltechdev/dockerserver/refs/heads/main/standard-install.sh | sh`


# Include Tailscale vpn (out of network access)
`curl -fsSL https://raw.githubusercontent.com/alltechdev/dockerserver/refs/heads/main/with-tailscale.sh | sh`


# Post Installation
Input http://localhost:5001 into your browser. From there you can access Dockge webui.


# Sources
**https://get.docker.com/** - _Docker/Docker Compose_
**https://github.com/louislam/dockge** - _Dockge_
**https://tailscale.com/install.sh** - _Tailscale Install Script_
