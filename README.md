# Docker template for working with tensorflow and keras.

### Build Docker

    docker build . -t signal_ai
    docker run --rm -it -v `pwd`:/app signal_ai:latest bash