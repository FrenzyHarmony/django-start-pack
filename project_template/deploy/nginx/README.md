Мы используем стандартный шаблонизатор `nginx` в `Docker` [+](https://hub.docker.com/_/nginx).


Шаблон с имение `default.conf.template` отрендерится с учетом переменных окружений
которые указанны в `docker-compose.yml->ngix->env_file` который в свою очередь возьмёт 
переменные окружения из `__env.env`.


Мы используем легковестный образ ОС(`alpine`) для `nginx`, но вы можете указть дургой образ ОС.