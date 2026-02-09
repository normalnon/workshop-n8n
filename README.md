# Workshop n8n
## Prerequisites
* docker
* docker-compose

```sh
# mac
brew install colima docker docker-compose

# ubuntu 
curl -fsSL https://get.docker.com | sh
```

## Run the n8n docker
```sh
docker-compose up -d
```

## Test your self-host n8n
```sh
# open the url in your browser
http://localhost:5678/
```

## NOTE
connecting other `localhost` service inside `n8n` e.g., ollama, crawl4ai
* replace `localhost` with `host.docker.internal`

