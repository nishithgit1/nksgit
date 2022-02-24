# Hi This Is Nishith
# 
# 1. install docker on ubantu
# 2. start and enable docker
#     systemctl start docker
#     systemctl enable docker 
#
# 3. Steps to launch mariadb container
#    1. run below command to lunch maria db container.
#    docker run --detach --name <some-mariadb> --env MARIADB_USER=<example-user> --env MARIADB_PASSWORD=<my_cool_secret> --env MARIADB_ROOT_PASSWORD=<my-secret-pw> mariadb:latest
#   2. check that container is running or not using below command.
#     docker ps 
#   3. connect mariadb container using below command.
#      docker exec -it <container name> bash
#   4. login to mariadb using below command.
#      mysql -u root -p      Enter passward : <provide root passward >
#   5. create database:
#      create database <database_name>;
#   6. to list of database :
#          show databases; 
#   7. to connect database. 
#        use <database_name>;
#   8. create table.
#   9. insert value in the table using below command.
#   10. show data of the table.
#      select * from <table_name>;  
