Выполняем команду чтобы сделать образ
docker build --help
Usage: docker build [OPTIONS] PATH | URL | -
к примеру docker build --tag test-server:v3 .

Выполняем команду запускаем образ с необходимыми параметрами
docker run --help
Usage: docker run [OPTIONS] IMAGE [COMMAND] [ARG...]
к примеру docker run -d -p 4567:80 test-server:v3
