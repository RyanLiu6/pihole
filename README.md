# pihole
Docker Pi-hole setup

# Setup
1. Clone the repo
2. Create `.env` with:

```
PASSWORD=<web UI Password>
DNS_DOMAIN=<some domain>
```

3. Run it!

```
docker-compose up -d
```

# Backups
1. Data is mounted at `$HOME/Data/pihole`
