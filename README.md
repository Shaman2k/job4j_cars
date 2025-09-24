# Проект "АвтоМаг"

## Описание проекта
На сайте должны быть объявления. В объявлении должно быть: описание, марка машины, тип кузова, фото.

Объявление имеет статус продано или нет.


## Технологии
- Java 17
- Spring Boot
- Thymeleaf
- Bootstrap 5
- Hibernate
- PostgreSQL
- Liquibase

## Требования
- Java 17+
- Maven 3.8+
- PostgreSQL 15+
- Liquibase 4.15.0

## Запуск проекта
1. Создать БД `cars`;
2. Настроить параметры подключения в `application.properties`;
3. Запустить проект:
  ```bash
  mvn spring-boot:run
  ```
4. Открыть в браузере: http://localhost:8080