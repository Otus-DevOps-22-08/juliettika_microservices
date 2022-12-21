# juliettika_microservices
juliettika microservices repository

## Docker 1-2
1. Установили docker, docker-compose и протестировали основные функции
2. Объяснили разницу между контейнером и образом
3. Установили docker-machine
4. Создали инстанс в yc, проинициализировали на нем докер хост систему
5. Подготовили файлы в репозитории для развертывания приложения, включая Dockerfile
6. Собрали образ, запустили контейнер и протестировали
7. Зарегистрировались в docker hub, запушили туда образ, запустили его у себя локально

## Docker 3
1. Разибили приложение на несколько компонентов
2. С помощью hadolint исправили ошибки в dockerfile
3. Запустили микросервисное приложение, проверили его работу
4. Оптимизировали docker-образы, добавили docker volume, проверили, что после перезапуска контейнеров пост остался на месте

## Docker 4
1. Разобрались с работой сети в Docker
2. Установить docker-compose на локальную машину
3. Собрать образы приложения reddit с помощью docker-compose
4. Запустить приложение reddit с помощью docker-compose

### Базовое имя проекта:

- Как образуется базовое имя проекта? ```<docker_compose_folder>_<service_name>_<incrementing_number_of_containers_with_same_name>```
- Как можно его задать? ```Установить свойство container_name для любого из контейнеров```
