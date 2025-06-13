# dockerserver
One command install script for debian based systems after OS installation. Standard install includes system update, Docker, Docker Compose and Dockge, a webui for managing docker compose.

Ubuntu Server is great for beginners: https://ubuntu.com/download/server


# Command
`curl https://raw.githubusercontent.com/alltechdev/dockerserver/refs/heads/main/standard-install.sh | sh`


# Include Tailscale vpn (out of network access)
`curl https://raw.githubusercontent.com/alltechdev/dockerserver/refs/heads/main/with-tailscale.sh | sh`


# Post Installation
Input http://localhost:5001 into your browser. From there you can access Dockge webui.


# Sources
**https://get.docker.com/** - _Docker/Docker Compose Install Script_

**https://github.com/louislam/dockge** - _Dockge_

**https://tailscale.com/install.sh** - _Tailscale Install Script_
