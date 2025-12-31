# Домашнее задание «Очереди RabbitMQ»
**Выполнил:** Даниил Дудников

## Задание 1. Установка RabbitMQ
![Веб-интерфейс RabbitMQ](screenshots/task1_rabbitmq_overview.png)

## Задание 2. Отправка и получение сообщений
### Очередь hello с сообщением (веб-интерфейс)
![Очередь hello в веб-интерфейсе](screenshots/task2_queue_with_message.png)

### Вывод consumer.py (терминал)
![Consumer output в терминале](screenshots/task2_consumer_output.png)

## Задание 3. Подготовка HA кластера
### Кластер из 2 нод (веб-интерфейс)
![Кластер из 2 нод](screenshots/task3_cluster_nodes.png)

### HA политика ha-all
![HA политика](screenshots/task3_ha_policy.png)

### Статус кластера на ноде 1 (команда)
![Cluster status node1](screenshots/task3_cluster_status_node1.png)

### Статус кластера на ноде 2 (команда)
![Cluster status node2](screenshots/task3_cluster_status_node2.png)

### Сообщение на ноде 1 (rabbitmqadmin)
![RabbitMQAdmin node1](screenshots/task3_rabbitmqadmin_node1.png)

### Сообщение на ноде 2 (rabbitmqadmin)
![RabbitMQAdmin node2](screenshots/task3_rabbitmqadmin_node2.png)

## Заключение
Все задания выполнены успешно:
1.  RabbitMQ установлен с веб-интерфейсом
2.  Настроена отправка и получение сообщений через очередь "hello"
3.  Создан HA кластер из двух нод с политикой репликации ha-all
4.  Проверена репликация сообщений между нодами
5.  Протестирована отказоустойчивость кластера
