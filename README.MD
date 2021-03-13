docker build . --tag ci-test --rm
docker run --env PORT=8080 ci-test