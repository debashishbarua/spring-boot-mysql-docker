# spring-boot-mysql-docker
Spring Boot mysql docker eample

#Docker Commands

$docker build -t accessing-data-mysql .
$docker run --name accessing-data-mysql -d --link sysql-dev-derver:db -9191:9191 accessing-data-mysql
