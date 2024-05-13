# Jenkins Configuration as Code

## How to run Jenkins with Configuration as Code

```bash
docker compose up -d
```

## How to stop Jenkins

```bash
docker compose down
```

## How to access Jenkins

Open your browser and go to [http://localhost:8080](http://localhost:8080)

## How to get the initial admin password

```bash
docker exec -it jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```

## How to access Jenkins logs

```bash
docker logs jenkins
```
