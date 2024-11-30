## Лабораторная № 1

- Развернул виртуалки у себя на локальной ОС(Windows) с помощью _Vagrantfile_ и команды ``vagrant up``
- В VirtualBox отобразились созданные виртуалки ![image](https://github.com/user-attachments/assets/28433857-0b56-433c-bc15-0915d3f7ccec)
- Написал скрипты по настройке созданных виртуалок в WSL:
- - ``clone_repo.yml`` - клонирование репозитория Django Python
  - ``install_docker.yml`` - установка Docker'а
  - ``run_app.yml`` - запуск приложения на виртуалках
  - ``inventory.ini`` - присвоение группы виртуалок имени app
