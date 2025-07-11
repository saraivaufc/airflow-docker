# airflow-docker
airflow-docker

## Make dirs

```shell
mkdir -p ./dags ./logs ./plugins ./config
```

## Create .env

```shell
echo -e "AIRFLOW_UID=$(id -u)" > .env
```

## Up containers

```shell
docker compose up
```