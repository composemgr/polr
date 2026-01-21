# Polr

A self-hosted polr application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/polr/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/polr" ~/.local/srv/docker/polr
cd ~/.local/srv/docker/polr
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install polr
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
