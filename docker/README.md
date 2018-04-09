# VIPCORP Docker (PHP 7.1-FPM - NGINX - Redis - ELK)

## Usage
1. Install docker and docker-compose 1.18 [here](https://docs.docker.com/compose/).

2. Configurable docker HTTP/HTTPS proxy [here](https://docs.docker.com/engine/admin/systemd/#httphttps-proxy).

3. Create a `.env` from the `.env.dist` file. Adapt it according to your application

   ```bash
   cp .env.dist .env
   ```
4. Build/run/stop containers with
     
    ```bash
    $ ./docker_build # build image
    $ ./docker_start # start containers
    $ ./docker_stop  # stop containers
    ```
5. Configurable Debug PHPStorm:
    * `port`: 9001
    * `host`: 172.17.0.1
    * `key`: 'PHPSTORM'

6. Enjoy :)