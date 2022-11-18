# Docker Downloads

Para downloads de aplicações Linux

Veja mais em [hub.docker.com/r/tmvdl/downloads](https://hub.docker.com/r/tmvdl/downloads)

## Como usar

Instalar o [Docker](https://docs.docker.com/engine/install/).

### Para baixar o RaspBerry SO

```
docker run -v $(pwd):/app -w /app --network host tmvdl/downloads:rasp
```

## License

[MIT](./LICENSE) 
