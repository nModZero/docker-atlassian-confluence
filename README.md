# Atlassian Confluence in a Docker container

This is a containerized installation of Atlassian Confluence with Docker. Currently no addons included.

## Getting Started

To quickly get started running a Confluence instance, use the following command:
```bash
docker run --detach --restart unless-stopped --publish 5100:8080 jwongartnet/docker-confluence:latest
```

Then simply navigate your preferred browser to `http://localhost:5100` and finish the configuration.