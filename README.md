# Backend-src-main-resources-application.properties
#configuration
server.port=8081
spring.jpa.hibernate.ddl-auto=update
spring.datasource.url=jdbc:mysql://database-2.cobegv9b6mue.ap-south-1.rds.amazonaws.com:3306/batch11
spring.datasource.username=admin
spring.datasource.password=adminadmin
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.hikari.maxLifetime= 600000

#spring.aws.secretsmanager.secretName=dev/mysql
#spring.aws.secretsmanager.endpoint=secretsmanager.ap-south-1.amazonaws.com
#spring.aws.secretsmanager.region=ap-south-1



management.endpoints.web.exposure.include=*
management.endpoint.shutdown.enabled=true
#endpoints.shutdown.enabled=true
