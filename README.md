# media_containers

My media containers

## Deploy

Create required external docker volumes and ensure media mountpoints exist on host and then:

```
docker-compose up -d
```

## Upgrade to latest version


```
docker-compose down && docker-compose up --build -d
```
