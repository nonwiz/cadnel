# Basic Cloudflared tunnel + Caddy

## Getting CF_API_TOKEN
1. Go to https://dash.cloudflare.com/[profile]/api-tokens
2. Manage Account (Bottom left)
3. Account API tokens
4. Create token
5. Use the template "Edit zone DNS"
6. Apply: Zone - Zone - Read, Zone - DNS - Edit
7. Include zone resources and save
8. Copy the token and save it in .env file as `CF_API_TOKEN`


## Reference:
- image: https://github.com/CaddyBuilds/caddy-cloudflare
- generating cf access token and other: https://blog.alexsguardian.net/posts/2023/12/04/caddyguide-part1/
