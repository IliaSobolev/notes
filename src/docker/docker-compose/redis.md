# Redis

```yaml
services:
  redis:
    image: redis:7.2.4
    restart: always
    ports:
      - "127.0.0.1:6379:6379"
    volumes:
      - "./data:/var/lib/redis"
```
