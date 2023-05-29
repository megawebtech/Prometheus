
Домашнее задание "Система мониторинга Prometheus"   Ярчак Александр

# Prometheus

Задание 1

Установите Prometheus.
Процесс выполнения

    Выполняя задание, сверяйтесь с процессом, отражённым в записи лекции
    Создайте пользователя prometheus
    Скачайте prometheus и в соответствии с лекцией разместите файлы в целевые директории
    Создайте сервис как показано на уроке
    Проверьте что prometheus запускается, останавливается, перезапускается и отображает статус с помощью systemctl

Требования к результату

    Прикрепите к файлу README.md скриншот systemctl status prometheus, где будет написано: prometheus.service — Prometheus Service Netology Lesson 9.4 — [Ваши ФИО]


Скачал Prometheus, разместил файлы  вцелевые директории, создал пользователя prometheus, создал сервис

https://github.com/megawebtech/Prometheus/blob/master/prometheus_service_running.JPG



Задание 2

Установите Node Exporter.
Процесс выполнения

    Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
    Скачайте node exporter приведённый в презентации и в соответствии с лекцией разместите файлы в целевые директории
    Создайте сервис для как показано на уроке
    Проверьте что node exporter запускается, останавливается, перезапускается и отображает статус с помощью systemctl

Требования к результату

    Прикрепите к файлу README.md скриншот systemctl status node-exporter, где будет написано: node-exporter.service — Node Exporter Netology Lesson 9.4 — [Ваши ФИО]


Скачал node exporter, создар сервис (как на уроке)

https://github.com/megawebtech/Prometheus/blob/master/node_exporter_service_running.JPG

Задание 3

Подключите Node Exporter к серверу Prometheus.
Процесс выполнения

    Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
    Отредактируйте prometheus.yaml, добавив в массив таргетов установленный в задании 2 node exporter
    Перезапустите prometheus
    Проверьте что он запустился

Требования к результату

    Прикрепите к файлу README.md скриншот конфигурации из интерфейса Prometheus вкладки Status > Configuration
    Прикрепите к файлу README.md скриншот из интерфейса Prometheus вкладки Status > Targets, чтобы было видно минимум два эндпоинта


Отредактировал файл конфигурации prometheus

Статус конфигурации из интерфейса prometheus:

https://github.com/megawebtech/Prometheus/blob/master/status_configuration.JPG




Статус targets:

https://github.com/megawebtech/Prometheus/blob/master/status_end_point.JPG

