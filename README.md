# cloudflared

## Setup
1. Create a `.env` file
2. Log into Cloudflare and go to `Zero Trust` > `Networks` > `Tunnels`
3. Click on the tunnel you are setting up (or set up a new one)
4. Find the tunnel token and past it into your `.env` file in the format `TUNNEL_TOKEN=TOKEN_VALUE_HERE`
5. Run `docker compose pull && docker compose up -d`
