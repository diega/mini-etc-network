## Mini ETC network
This is a minimal isolated environment for testing peering between [core-geth](https://core-geth.org/) and [besu](https://besu.hyperledger.org) using ETC Mainnet consensus.

### Running
```shell
$ docker compose up -d
```

### Logs
```shell
$ docker compose logs -f <geth-1 | besu-1>
```