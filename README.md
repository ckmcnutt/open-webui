# Open WebUI Config
Docker compose config for local open-webui instance.

## Installation

```bash
# Clone repo
git@github.com:ckmcnutt/open-webui.git

# Generate WEBUI_SECRET_KEY and write it to a .env file
echo "WEBUI_SECRET_KEY=$(openssl rand -hex 32)" > .env

# Run
docker compose up -d
```