# salute-demo-app

#### Для работы необходимо создать смартап, сгенерировать токен и запустить проект.

## Создание смартапа:

1. Идём на страницу SmartApp Studio ([ссылка](https://smartapp-studio.sberdevices.ru/));
1. Нажимаем "Создать смартап";
1. Указываем "Название смартапа" (указываем это же название в файле ".env.sample", в строке "REACT_APP_SMARTAPP");
1. Переключаем "Выбор типа смартапа" на "Canvas App";
1. Переключаем "Выбор инструмента" на "Есть готовое приложение";
1. Указываем URL на "Webhook";
1. Указываем URL на "Frontend Endpoint";
1. Нажимаем "Создать смартап";

## Генерация токена:

1. Идём на страницу SmartApp Studio ([ссылка](https://smartapp-studio.sberdevices.ru/));
1. В меню пользователя (правый верхний угол) выбираем "Настройки профиля";
1. Нажимаем "Auth Token";
1. Нажимаем "Обновить ключ";
1. Нажимаем "Скопировать ключ" (сейчас токен в буфере);
1. Указываем токен в файле ".env.sample", в строке "REACT_APP_TOKEN".
1. Переименовываем файл ".env.sample" в ".env";

## Запуск проекта:

```bash
npm install

npm run start
```
