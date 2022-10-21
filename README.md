# CrudWeb
Необходимо реализовать веб приложение, которое взаимодействует с БД.

Сущности:   
Skill (id, name)    
User(id, firstName, lastName, specialty, Set\<Skill> skills)  
Team(id, name, Set\<User> users)  
Project(id, name, budget, Set\<Team> teams)    
Customer(id, name, Set\<Project> projects)   

Требования:
 
1. Все CRUD операции для каждой из сущностей    
2. Придерживаться подхода MVC   
3. Для сборки проекта использовать Maven    
4. Для взаимодействия с БД - Hibernate  
5. Для конфигурирования Hibernate - аннотации   
6. Инициализация БД должна быть реализована с помощью liquibase
7. Взаимодействие с пользователем необходимо реализовать с помощью Servlets + Thymeleaf 
8. Приложение должно быть развёрнуто на https://www.heroku.com/

1. 每个实体的所有 CRUD 操作
2.坚持 MVC 方法
3.要生成项目，请使用 Maven
4.与数据库交互 - Hibernate
5.用于配置Hibernate - 注释
6.数据库初始化必须使用liquibase实现
7.用户交互必须使用 Servlets + Thymeleaf实现 
