# docker-bitcore
A dockerized bitcore

```
docker run -d \
  --restart=always \
  --name bitcore \
  -p 3001:3001 \
  -p 8333:8333 
  -p 6667:6667 \
  -v /srv/bitcore:/root/.bitcore \
  patrickhempel/bitcore 
```
