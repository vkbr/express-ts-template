# Familiar API

## Development

1. Create docker postgres instance
   ```sh
   docker run \
      --name {{app}} \
      -p 5432:5432 \
      -e POSTGRES_PASSWORD=pw \
      -e POSTGRES_USER={{app}}-user \
      -e POSTGRES_DB={{app}} \
      -d postgres:15
   ```
