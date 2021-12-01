# Docker compose PGadmin example setup

Quick steps

1. Install [Docker-Compose](https://docs.docker.com/compose/install/)
2. Install [GIT](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
3. Open a [terminal](https://towardsdatascience.com/a-quick-guide-to-using-command-line-terminal-96815b97b955) 
4. Checkout this repository via `git clone https://github.com/ag-gipp/docker-pgadmin.git`
5. Start the containers via `docker-compose up -d`
6. Navigate to your [local pg-amdin web ui](http://localhost:5050)
7. Log in with the credentials from the [docker-compose file](https://github.com/ag-gipp/docker-pgadmin/blob/58f23d6fbebdf9c1f3ea3d4e9953d87c4a9c9627/docker-compose.yml#L17-L19)
```dockerfile
      PGADMIN_DEFAULT_EMAIL: admin@admin.com
      #Change this password
      PGADMIN_DEFAULT_PASSWORD: MFSYTZVH9HPHL92A
```
