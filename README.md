# КТ 8 DevOps
Многоконтейнерное приложение, развернутое с помощью Docker Compose, включающее:
* Flask (backend)
* PostgreSQL (база данных)
* Nginx (обратный прокси и статика)

## Установка и запуск
1. Клонируйте репозиторий:
```bash
git clone https://github.com/JustKirill1/kt8-devops.git
cd kt8-devops
```
2. Запуск
```bash
docker-compose up -d
```
## Доступ к приложению
После запуска приложение будет доступно:
* Flask API: http://localhost:5000
* Nginx: http://localhost:80
* PostgreSQL http://localhost:5432
