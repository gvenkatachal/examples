### NOTES

For Sinatra/Thin apps you MUST make at least one HTTP call, so the app gets a chance to load extra dependencies it needs.

The `_docker-slim.env` file declares the environment variables required by the `docker-slim` helper scripts (in `_docker-slim`). The helper scripts in `_docker-slim` allow you to do everything you need with the app container (create/run/minify/etc). See [`_docker-slim/README.md`](_docker-slim/README.md) for more details.
