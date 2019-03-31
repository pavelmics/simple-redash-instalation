#INSTALLATION
1. Create external postgresql server
2. Create database at the server
3. Add database connection string to docker-compose.yml file
4. Change REDASH_COOKIE_SECRET to some custom value
4. Run docker-compose up -d
5. Run `docker exec -it redash-web bin/docker-entrypoint create_db`
6. See localhost 5000