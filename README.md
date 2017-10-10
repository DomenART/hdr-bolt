# House Design Room

## Build Setup

``` bash
# установка зависимостей
npm install

# хапуск сборки для разработки
npm run dev

# запуск сборки для продакшена
npm run build
```
## Bolt

``` bash
# 1. Заходим в контейнер докера
docker-compose exec --user $(id -u) php bash

# 2. Заходим в папку с проектом
cd path

# 3. Установка зависимостей компосера
composer install

# 4. Выходим из контейнера
exit

# 5. Установка зависимостей npm
npm install
```