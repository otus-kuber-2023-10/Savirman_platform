В ходе проделанной работы выполнено следующее:
- Создан CustomResourceDefinition mysql.otus.homework и CustomResource mysql-instance
- Создан custom controller mysql-operator.py
- Произведен деплой созданного операора
- Прооведена проверка работоспособности

Вывод при запущенном MySQL приложен в файле mysql.output.

Вывод команды kubectl het jobs:
NAME                         COMPLETIONS   DURATION   AGE
backup-mysql-instance-job    1/1           3s         32m
restore-mysql-instance-job   1/1           53s        32m
