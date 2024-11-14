# telegram-bot-kotlin-template
Sample code for telegram bot with Spring and Kotlin

Please, generate your telegram bot name before use. And change properties bot.username and bot.token in application.yml file

```yml
bot:
  username: // write your username
  token: // write your token
spring:
  datasource:
    url: jdbc:postgresql://localhost:5432/kotlin_template
    username: postgres
    password: postgres
```

Before use this example bot try to create database and do command

```bash
/gradelw flywayMigrate
```

Don't forget change your properties in [build.gradle.kts](build.gradle.kts)

Create bot https://tlgrm.ru/docs/bots
