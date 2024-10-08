# simple-docker-postgres


curl https://raw.githubusercontent.com/paihari/simple-docker-postgres/main/docker-compose.yml -o docker-compose.yml


sudo -E DB_PORT=5432 POSTGRES_PASSWORD=yourpassword POSTGRES_DB=yourdb MOUNT_PATH=/mnt/path docker compose up -d



