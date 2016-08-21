## Docker

Run DataCite infrastructure locally using Docker.

```
cp .env.example .env
docker-compose up
```

You probably want to customize `.env`. The list of variables in `.env.example` is work in progress.

### Supported services

* [API](https://api.datacite.org): http://localhost:8040
* [Assets](https://assets.datacite.org): http://localhost:8010
* [Blog](https://blog.datacite.org): http://localhost:8030
* [Bot](https://bot.datacite.org): http://localhost:9000
* [Content Resolver](https://data.datacite.org): http://localhost:8070
* [Event Data](https://eventdata.datacite.org): http://localhost:8050
* [Homepage](https://www.datacite.org): http://localhost:8060
* [Profiles](https://profiles.datacite.org): http://localhost:8080
* [Schema](https://schema.labs.datacite.org): http://localhost:8020
* [Search](https://search.datacite.org): http://localhost:8000

We are also running the following services for persistent storage, using the official Docker containers:

* MySQL (5.6)
* Redis (2.8)
