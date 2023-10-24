Установка docker-ce для Ubuntu 20.04 и CentOS 8.
Установка postgresql+psycopg2. Создание базы и пользователя к ней.
Для проектной работы № 6 по Ansible.

---

Подробнее:

В inventory vm2(Ubuntu) и vm3(CentOS) находятся в группе app, vm1(Ubuntu) — в группе database и web:
- на машинах группы app выполняется установка и запуск Docker;
- на машинах группы database выполняется установка и запуск postgresql-server (версия postgesql и data-директория являются переменными, задающиеся в inventory).
