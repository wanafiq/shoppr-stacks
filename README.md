# Shoppr Stacks

This project centralizes the infrastructure stacks required for local development.

## Getting Started

To run the stacks:

1.  Ensure you have Docker and Docker Compose installed.
2.  Navigate to the directory containing this `README.md` and the `docker-compose.yaml` file.
3.  Run the command:
```shell
  docker-compose up -d
```

To stop and remove the running containers:

Navigate to the directory containing the docker-compose.yaml file (if you are not already there).
Run the command:
```shell
  docker-compose down
```

## Accessing Minio

* **Minio Server API:** Accessible on your host at `http://localhost:9000`.
* **Minio Console:** Accessible on your host at `http://localhost:9001`. Use the credentials `minioadmin` for the username and `password123` for the password.

## Data Persistence

Minio data is persisted in the `./data/minio` directory on your host machine.