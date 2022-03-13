## Background
The project is intended to start learning load balancing technique. This can minimize anxiety of installing different services to start the playground. [A blog in dev.to](https://dev.to/abidkhan484/load-balancing-playground-with-nginx-and-docker-1fc1) is assosiated with the repo.

## Prerequisites:
- Virtual Machine
- Docker
- Docker Compose

## Project tree:
```sh
.
├── README.md
├── docker-compose.yml
├── lb-conf
│   └── default.conf
```
## Playground:
1. Clone the repo : 

    ```sh
    git clone https://github.com/abidkhan484/nginx-load-balancing-docker.git
    ```

2. Start the application :

    ```sh
    docker-compose up -d
    ```

    **Please wait this might take a several minutes...**

    ```sh
    docker-compose logs -f # Follow log output
    ```

3. Open your favorite browser :

    * [http://localhost:8100](http://localhost:8100/)

4. Stop and clear services

    ```sh
    docker-compose down -v
    ```
