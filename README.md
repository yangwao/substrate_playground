# substrate_playground

[Requirements here is to have Docker installed](https://docs.docker.com/get-docker/)

## Run for local develop Edgeware with EVM support

```
docker-compose -f edgeware_frontier.yml up
```

## Run for local develop Edgeware

```
docker-compose up
```

## Run for Beresheet (testnet)
```
docker-compose -f beresheet.yml
```

### Run for Mainnet Edgeware
```
docker-compose -f mainnet.yml
```
### Credits

Thanks to [twitter.com/EliottTeiss](https://twitter.com/EliottTeiss) for making [ETeissonniere/substrate-nodeops](https://github.com/ETeissonniere/substrate-nodeops)

We are using thats image to spin up great developer experience. Give him kudos 🙌
