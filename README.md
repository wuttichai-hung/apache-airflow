- Add fernet_key
```
mkdir -p ./dags ./logs ./plugins ./data
```

```
echo -e "AIRFLOW_UID=$(id -u)" > .env
```

```
docker build -t h-airflow .
```

```
docker-compose up -f
```
