# receipts-base

https://d5dju5qjvcekak33bfgv.apigw.yandexcloud.net

## Обновление бекэнда

- Сконфигурировать `yc` для работы с нужным облаком
- Сконфигурировать `docker` для работы с нужным regestry облака
- Установить переменные окружения из файла `deploy/.export.example`
- Запустить файл `bash backend/update.sh`

## Обновление фронтэнда

- Сконфигурировать `yc` для работы с нужным облаком
- Сконфигурировать `s3cmd` для работы с нужным s3 хранилищем облака
- Установить переменные окружения из файла `deploy/.export.example`
- Запустить файл `bash front/update.sh`

Не откладывать все на последний день...