1. Что такое системы управления конфигурациями
1) Создать и настроить репозиторий в gitlab / github
1.1) Создать feature-branch для merge request
2) Создать простой плейбук, в котором:
2.1) Создать базовую директорию на сервере
2.2) Скачать произвольный файл из интернета
2.3) Установить несколько пакетов ОС: htop,unzip,telnet,java,python
2.4) Развернуть nginx на целевой сервер, после установки и запуска выполнить запрос на <nginx_host>:<nginx_port>/ и проверить 200 response_code
2.5*) Создать jinja template (module template) nginx.conf, и шаблонизировать в нем nginx.port
2.6*) Создать пользователя ОС с кастомным паролем

Jinja2 doc: jinja2docs.readthedocs.io
Ansible doc: https://docs.ansible.com, https://docs.ansible.com/ansible/latest/user_guide/index.html

Для сдачи ДЗ прислать ссылку на merge request с gitlab / github
