# Apache SuperSet

## Table of Contents
* [Development](#Development)
  * [Prerequisites](#Prerequisites)
  * [Build](#Build)
  * [Run](#Run)
  * [Test](#Test)
* [Operations](#Operations)
* [Support](#Support)

## Development
docker-compose up
### Prerequisites

```shell
apt install docker
apt install docker-compose git
cd /opt
git clone https://github.com/ursais/superset
```

### Build

```shell
docker-compose build
```

### Run

```shell
docker-compose up
```
### Stop
```shell
docker-compose down
```
### Test

```shell
docker-compose run odoo --test-enable --workers=0 --stop-after-init -d <DATABASE NAME>  -i <ADDONS>
```

## Operations

Take a look at [README.md](./helm/README.md)

## Support

Report any issue to this
[Github project](https://github.com/ursais/superset-template/issues).
