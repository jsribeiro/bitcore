# Supported tags and respective `Dockerfile` links
* `3.0.0`, `3.0`, `3`, `latest` ([Dockerfile])

[![](https://imagelayers.io/badge/sena/bitcore:latest.svg)](https://imagelayers.io/?images=sena/bitcore:latest 'Get your own badge on imagelayers.io')

## Bitcore
Infrastructure to build Bitcoin and blockchain-based applications for the next generation of financial technology.

[Bitcore]

```
docker run -d --restart=always --name bitcore \
   -p 3001:3001 -p 8333:8333 \
   -v bitcore_data:/root/.bitcore \
   sena/bitcore
```

[Dockerfile]: <https://github.com/jsribeiro/bitcore/blob/master/Dockerfile>
[Bitcore]: <https://github.com/bitpay/bitcore>
