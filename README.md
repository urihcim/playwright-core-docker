# playwright-core-docker

This repository provides lightweight Docker images containing `playwright-core`. Images are available for both Node.js and Bun environments.

## Available Images

- Node.js based: `Dockerfile.node`
- Bun based: `Dockerfile.bun`

## Container Packages

Images are published to GitHub Container Registry:  
[https://github.com/urihcim/playwright-core-docker/pkgs/container/playwright-core](https://github.com/urihcim/playwright-core-docker/pkgs/container/playwright-core)

## How to Build

### Node.js Image

```sh
docker build -f Dockerfile.node -t playwright-core:node .
```

### Bun Image

```sh
docker build -f Dockerfile.bun -t playwright-core:bun .
```

## License

[MIT License](LICENSE)
