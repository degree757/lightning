crond [![Release](https://img.shields.io/github/release/degree757/cron-s.svg)](https://github.com/degree757/cron-s/releases)
=====================

crond is a distributed task scheduling system based on raft, time-heap in go.

| Web | Admin |
|:-------------:|:-------:|
|![list](docs/list.png)|![add](docs/add.png)|


## Overview
./crond agent --http-port :7570 --node-id n2 --bind :8570 --data-dir data/n2

./crond agent --http-port :7571 --node-id n3 --bind 127.0.0.1:8571 --data-dir data/n3 --join 127.0.0.1:7570

./crond agent --http-port :7572 --node-id n4 --bind 127.0.0.1:8572 --data-dir data/n4 --join 127.0.0.1:7570

## Installation

- [Install from binary]()
- [Install from source]()
- [Ship with Docker]()

### Tutorials

- todo

## License

This project is under the MIT License. See the [LICENSE](https://github.com/degree757/cron-s/blob/master/LICENSE) file for the full license text.
