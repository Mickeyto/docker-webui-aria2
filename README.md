# README
[中文文档](README_CN.md)
# docker env_file
```bash
cp .env-template .env

//content

// generate RPC_SECRET ./bin/generate-secret
RPC_SECRET=bb413b88-6f0e-4c51-98aa-a5662849aa69
WEBUI_LOCAL_PORT=8081
WEBUI_CONTAINER_PORT=80

//
```

## Usage
`docker-compose`:

```sh
# generate RPC_SECRET
./bin/generate-secret

# Start the project

docker-compose up -d

//default port 8081
http://localhost:8081/
```

## Links

* [timonier docker webui-aria2](https://hub.docker.com/r/timonier/webui-aria2/)
