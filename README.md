<img
  src="https://github.com/apache/superset/raw/master/superset-frontend/src/assets/branding/superset-logo-horiz-apache.png"
  alt="Superset"
  width="500"
/>

## Development
```shell
docker-compose --env-file docker/.env build
docker-compose --env-file docker/.env up
```
### Prerequisites

```shell
apt install docker
apt install docker-compose git
cd /opt
git clone https://github.com/ursais/superset
```

### Run from latest built image
```shell
docker-compose -f docker-compose-non-dev.yml up
```
### Stop
```shell
docker-compose down
```
### Test

```shell
docker-compose run odoo --test-enable --workers=0 --stop-after-init -d <DATABASE NAME>  -i <ADDONS>
```

Report any issue to this
[Github project](https://github.com/ursais/superset-template/issues).
