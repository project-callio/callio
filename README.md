# Callio - control your automated testing

## Running

```
docker-compose up -d
```

## Configuration

### Callio API

- `RUST_LOG` - setup logging level for backend
- `SECRET_KEY` - set default secret key
- `DATABASE_URL` - url to connect to PostgreSQL in format `postgres://<username>:<password>@<host>:<port>/<db_name>`
- `NATS_USERNAME` - NATS username
- `NATS_PASSWORD` - NATS password
- `NATS_URL` - NATS url in format `nats://<host>:<port>`

Default port for backend is `8000`

### Callio UI
- `NEXT_PUBLIC_CALLIO_API_HOST` - url to access Callio API with `/url` basepath

Default port for frontend is `3000`
