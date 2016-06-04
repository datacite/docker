## Docker

Run DataCite infrastructure locally using Docker.

```
cp .env.example .env
docker-compose up
```

You probably want to customize `.env`.

### Supported services

* [Labs Search](https://search.labs.datacite.org): http://localhost:8000
* [Assets](https://assets.datacite.org): http://localhost:8010
* [Labs Schema](https://schema.labs.datacite.org): http://localhost:8020
* [Blog](https://blog.datacite.org): http://localhost:8030

We are also running the following services for persistent storage, using the official Docker containers:

* MySQL (5.6)
* Redis (2.8)
