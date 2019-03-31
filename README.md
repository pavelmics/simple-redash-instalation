#INSTALLATION
1. Rename `redash.env.example` to `redash.env`;
2. Change redash.env according to your settings. External postgresql server is required. As a email settings you can use free smtp servers like gmail.com (tested with mail.ru)
3. Run `docker-compose up -d`
4. Run `docker exec -it redash-web bin/docker-entrypoint create_db` to initialize database with empty redash ddl;
5. Go to <you-ip-or-hostname>:5000 for details;
