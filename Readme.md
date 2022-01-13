# opensea-images-downloader

Script to download all the images from an opensea collection using the OpenSea API

#### Docker version

- Docker and Docker compose installed (https://docs.docker.com/get-docker/ - https://docs.docker.com/compose/install/)

`)


### Running in docker

To run in docker (easiest / recommended mode) just clone the project, cd into it and run this command:

    docker-compose run -e COLLECTION_NAME=boredapeyachtclub makevoid/opensea_downloader

Check the `output` directory which will contain the downloaded images.

---

