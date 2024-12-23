# infra-common

This creates the containers that are required downstream by certain applications

### zcaudate-xyz/infra-redis

docker run zcaudate-xyz/infra-redis:main


### push to docker.io

```
docker pull ghcr.io/zcaudate-xyz/infra-redis:main && docker tag ghcr.io/zcaudate-xyz/infra-redis:main zcaudate-xyz/infra-redis:main && docker push zcaudate-xyz/infra-redis:main
docker pull ghcr.io/zcaudate-xyz/infra-net:main && docker tag ghcr.io/zcaudate-xyz/infra-net:main zcaudate-xyz/infra-net:main && docker push zcaudate-xyz/infra-net:main
docker pull ghcr.io/zcaudate-xyz/infra-db:main && docker tag ghcr.io/zcaudate-xyz/infra-db:main zcaudate-xyz/infra-db:main && docker push zcaudate-xyz/infra-db:main
docker pull ghcr.io/zcaudate-xyz/infra-ganache:main && docker tag ghcr.io/zcaudate-xyz/infra-ganache:main zcaudate-xyz/infra-ganache:main && docker push zcaudate-xyz/infra-ganache:main
docker pull ghcr.io/zcaudate-xyz/infra-ganache-test:main && docker tag ghcr.io/zcaudate-xyz/infra-ganache-test:main zcaudate-xyz/infra-ganache-test:main && docker push zcaudate-xyz/infra-ganache-test:main
docker pull ghcr.io/zcaudate-xyz/infra-expo:main && docker tag ghcr.io/zcaudate-xyz/infra-expo:main zcaudate-xyz/infra-expo:main && docker push zcaudate-xyz/infra-expo:main
```
### recovery from docker.io

```
docker pull zcaudate-xyz/infra-redis:main && docker tag zcaudate-xyz/infra-redis:main ghcr.io/zcaudate-xyz/infra-redis:main
docker pull zcaudate-xyz/infra-net:main && docker tag zcaudate-xyz/infra-net:main ghcr.io/zcaudate-xyz/infra-net:main
docker pull zcaudate-xyz/infra-db:main && docker tag zcaudate-xyz/infra-db:main ghcr.io/zcaudate-xyz/infra-db:main
docker pull zcaudate-xyz/infra-ganache:main && docker tag zcaudate-xyz/infra-ganache:main ghcr.io/zcaudate-xyz/infra-ganache:main
docker pull zcaudate-xyz/infra-ganache-test:main && docker tag zcaudate-xyz/infra-ganache-test:main ghcr.io/zcaudate-xyz/infra-ganache-test:main
docker pull zcaudate-xyz/infra-expo:main && docker tag zcaudate-xyz/infra-expo:main ghcr.io/zcaudate-xyz/infra-expo:main
```
