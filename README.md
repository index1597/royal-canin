# Royal Canin

## Должно быть установлено

node.js - https://nodejs.org/

npm

```bash
$ npm install -g npm
```

bower

```bash
$ npm install -g bower
```

gulp

```bash
$ npm install -g gulp
```

## Настройка окружения

```bash
$ bower i
$ npm i
$ gulp
```
Запустится сервер http://localhost:3000

## Как и где работаем

Вся работа ведется в **src/**

### Сборка

По умолчанию сборка происходит в **build/** (меняется в gulp/config.js).

### Таски

Можно запускать отдельно таски, например:

```bash
$ gulp sass
```

или

```bash
$ gulp watch
```

### Рекомендации

#### Конфигурация
Минификация html/css/js настраивается в gulp/config.js

#### Описание основных файлов/папок проекта (src/)
Название файла  | Содержание файла
----------------|----------------------
index.html      | Главный файл проекта
internal.js     | Основной файл скриптов в котором собирается все скрипты проекта 
external.js     | Дополнительный файл скриптов, который собирает все скрипты/библиотеки
internal.scss   | Основной файл стилей в котором собираются все части модулей проекта
external.scss   | Дополнительный файл стилей, который собирает все стили плагинов
templates/      | Шаблоны частей проекта (шапка, подвал, боковая панель, главное меню и прочее)