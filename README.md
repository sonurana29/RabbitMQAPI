# RabbitMQAPI
Step 1:- download project and build
#Entity Framework command
Step 2
add-migration “first”
update-database
#Docker
Step 3:- Docker open and running
Step 4:- Run below  docker command
            3.1 docker pull rabbitmq:3-management
          3.2 docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:3-management
Run above command then open below url
http://localhost:15672/#/
UserName/Password = guest/guest

