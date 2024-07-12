#### Сборка образа:
docker build ./ --tag=My_Hw1.


#### Запуск контейнера:
docker run --name homeworks -d -p 8769:6060 My_Hw1.