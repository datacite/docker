## Docker

Run DataCite infrastructure locally using Docker.

```
cp .env.example .env
docker-compose up
```

You probably want to customize `.env`.

### Supported services

* [DataCite Labs Search](https://search.labs.datacite.org)
* [DataCite Labs Schema](https://schema.labs.datacite.org)
* [DataCite Blog](https://blog.datacite.org)
* [DataCite Assets](https://assets.datacite.org)

We are also running the following services for persistent storage

* MySQL (5.6)
* Redis (2.8)
