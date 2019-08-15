## env_file 配置
```bash
//配置 .env 文件
cp .env-template .env

//可配置项，生成 RPC_SECRET 命令：./bin/generate-secret

RPC_SECRET=bb413b88-6f0e-4c51-98aa-a5662849aa69
WEBUI_LOCAL_PORT=8081
WEBUI_CONTAINER_PORT=80

//
```

## 使用
`docker-compose`:

```sh

# 启用

docker-compose up -d

//本地默认端口 8081
http://localhost:8081/
```

## Links

* [timonier docker webui-aria2](https://hub.docker.com/r/timonier/webui-aria2/)
