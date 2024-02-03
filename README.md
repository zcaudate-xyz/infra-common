# infra-build

#### pushing to docker.io

```
docker pull ghcr.io/zcaudate-xyz/infra-redis:main && docker tag ghcr.io/zcaudate-xyz/infra-redis:main zcaudate/infra-redis:main && docker push zcaudate/infra-redis:main
docker pull ghcr.io/zcaudate-xyz/infra-net:main && docker tag ghcr.io/zcaudate-xyz/infra-net:main zcaudate/infra-net:main && docker push zcaudate/infra-net:main
docker pull ghcr.io/zcaudate-xyz/infra-db:main && docker tag ghcr.io/zcaudate-xyz/infra-db:main zcaudate/infra-db:main && docker push zcaudate/infra-db:main
docker pull ghcr.io/zcaudate-xyz/infra-ganache:main && docker tag ghcr.io/zcaudate-xyz/infra-ganache:main zcaudate/infra-ganache:main && docker push zcaudate/infra-ganache:main
docker pull ghcr.io/zcaudate-xyz/infra-ganache-test:main && docker tag ghcr.io/zcaudate-xyz/infra-ganache-test:main zcaudate/infra-ganache-test:main && docker push zcaudate/infra-ganache-test:main
docker pull ghcr.io/zcaudate-xyz/infra-expo:main && docker tag ghcr.io/zcaudate-xyz/infra-expo:main zcaudate/infra-expo:main && docker push zcaudate/infra-expo:main
```
#### recovery from docker.io

```
docker pull zcaudate/infra-redis:main && docker tag zcaudate/infra-redis:main ghcr.io/zcaudate-xyz/infra-redis:main
docker pull zcaudate/infra-net:main && docker tag zcaudate/infra-net:main ghcr.io/zcaudate-xyz/infra-net:main
docker pull zcaudate/infra-db:main && docker tag zcaudate/infra-db:main ghcr.io/zcaudate-xyz/infra-db:main
docker pull zcaudate/infra-ganache:main && docker tag zcaudate/infra-ganache:main ghcr.io/zcaudate-xyz/infra-ganache:main
docker pull zcaudate/infra-ganache-test:main && docker tag zcaudate/infra-ganache-test:main ghcr.io/zcaudate-xyz/infra-ganache-test:main
docker pull zcaudate/infra-expo:main && docker tag zcaudate/infra-expo:main ghcr.io/zcaudate-xyz/infra-expo:main
```
