По мотивам https://habr.com/ru/companies/slurm/articles/704208/  
Консольные команды

Войти в контейнер через RabbitMQ (чтобы выполнять команды Rabbit надо находиться на сервере с Rabbit):
```docker-compose exec rabbitmq bash```  

docker-compose up --build -d --remove-orphans --force-recreate && docker-compose logs -f

http://111.222.333.444:15672/

