# futafi/x11-socket

# 説明
ソケットを共有する方法

# 使い方

set .env file
```bash
$ echo -e "UID=$(id -u)\nGID=$(id -g)" > .env
```

build docker image
```bash
$ docker-compose build --build-arg USER_NAME="developer"
```

run image
```bash
$ docker-compose run ubuntu bash
```
