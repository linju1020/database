# database
docker-compose.yml for postgresql and mssql


---------------
Q&A
#### Some services (mssql) use the 'deploy' key, which will be ignored. Compose does not support 'deploy' configuration - use `docker stack deploy` to deploy to a swarm.
```bash
docker-compose --compatibility up -d
```
