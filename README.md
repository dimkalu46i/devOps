`requirements.yml` - зависимости для установки Docker & Nginx из GitLab

`templates` - шаблоны конфиг файлов для Nginx & default-сайта

`roles` - роли для установки Nginx & Docker

`playbook.yml` - плейбук для установки через роль Nginx - Nginx на хост группы [web], через роль Docker - Docker на хост группы [app]

`inventory.ini` - инвентори-файл с описанием хостов
