# PostgreSQL

```yaml
services:
  postgres:
    image: postgres:16.2
    restart: always
    environment:
      POSTGRES_DB: "dbname"
      POSTGRES_PASSWORD: "superpassword"
    ports:
      - "127.0.0.1:5432:5432"
    volumes:
      - "./data:/var/lib/postgresql/data"
```

***Replace `dbname` and `superpassword` with your values**
