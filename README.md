# BigBlueButton Docker Fork
This is a fork of https://github.com/alangecker/bigbluebutton-docker. It is modified for the needs of my own server.

## Install
1. Install docker-ce & docker-compose
    1. follow instructions
        * Debian: https://docs.docker.com/engine/install/debian/
        * CentOS: https://docs.docker.com/engine/install/centos/
        * Fedora: https://docs.docker.com/engine/install/fedora/
        * Ubuntu: https://docs.docker.com/engine/install/ubuntu/
    2. Ensure docker works with `$ docker run hello-world`
    3. Install docker-compose: https://docs.docker.com/compose/install/
    4. Ensure docker-compose works: `$ docker-compose --version`
5. Clone this repository
   ```sh
   $ git clone --recurse-submodules https://github.com/alangecker/bigbluebutton-docker.git bbb-docker
   $ cd bbb-docker
   ```
6. Run setup:
   ```bash
   $ ./scripts/setup
   ```
7. Start containers:
    ```bash
    $ ./scripts/compose up -d
    ```

## Special thanks to
- @alangecker - This repository is forked from him. 
