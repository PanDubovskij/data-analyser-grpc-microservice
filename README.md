# Data analyser gRPC microservice

This application receives data
from [Data generator gRPC service](https://github.com/PanDubovskij/data-generator-grpc-microservice)
with gRPC.

This application can return data to [Data store gRPC service](https://github.com/PanDubovskij/data-store-grpc-microservice)

### Usage

To start an application you need to pass variables to `.env` file.

You can use example `.env.example` file with some predefined environments.

You can find Docker compose file in `docker/docker-compose.yaml`.

Application is running on port `8082`.

All insignificant features (checkstyle, build check, dto validation) are not
presented.

### Docker

You can run all course applications via `docker-compose.yaml` from `docker`
folder.

It contains all needed configs.

Note that all services must be in the same network to communicate with each
other.