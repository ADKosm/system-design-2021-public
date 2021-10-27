Запускать руками все команды для разных конейтеров - непросто.

Поэтому придумали docker-compose - систему конфигурирования запуска контейнеров. 

Установить - https://docs.docker.com/compose/install/

Конфигурация описана в "docker-compose.yaml"

Больше информации про то, как это работает - https://docs.docker.com/compose/

Попробуем собрать и запустить написанную конфигурацию. Запускать команду необходимо из директории, в которой написана сама конфигурация.

```bash
docker-compose up --build
```
