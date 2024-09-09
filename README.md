# Red Hat Developer Hub for podman compose

## Setup

Copy the `env.example` file to `.env` and fill in the required values.

## Configuration

Edit `app-config.local.yaml` to configure RHDH. Edit `dynamic-plugins.yaml` to configure dynamic plugins.

## Running the compose file

```bash
podman-compose up
```

Now connect to `https://localhost:7007` to see the Red Hat Developer Hub.