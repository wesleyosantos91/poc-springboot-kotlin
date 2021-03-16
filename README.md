<div align="center">

![](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange)
</div>

<div align="center">

# POC - CRUD SPRING BOOT - KOTLIN.
O projeto tem como objetivo demonstrar a ultilização do Kotlin com SpringBoot, com um crud de Pessoa.

![](https://img.shields.io/badge/Autor-Wesley%20Oliveira%20Santos-brightgreen)
![](https://img.shields.io/badge/Language-Kotlin-brightgreen)
![](https://img.shields.io/badge/Framework-Springboot-brightgreen)
![](https://img.shields.io/badge/HTTP-Restful-brightgreen)

</div> 

## Fundamentos teóricos

> O Spring é um framework open source para a plataforma Java criado por Rod Johnson e descrito em seu livro "Expert One-on-One: JEE Design e Development". Trata-se de um framework não intrusivo, baseado nos padrões de projeto inversão de controle e injeção de dependência..

> Kotlin: Kotlin é uma Linguagem de programação multiplataforma, orientada a objetos e funcional, concisa e estaticamente tipada, desenvolvida pela JetBrains em 2011, que compila para a Máquina virtual Java e que também pode ser traduzida para a linguagem JavaScript e compilada para código nativo.

## Tecnologias
- Kotlin 1.4.30 
- Spring Boot 2.2.7.RELEASE
   - spring-boot-starter-web
   - spring-boot-starter-data-jpa
   - spring-boot-devtools
- Flywaydb
- H2
- Tomcat (Embedded no Spring Boot)
- GIT

## Execução

A execução das aplicações são feitas através do de um comando Gradle que envoca a inicialização do Spring Boot.

- Scripts
  ### Executar a aplicação
    - 1° comando: ``` ./gradlew build```
    - 2° comando: ```./gradlew bootRun```

## Utilização
- Cliente http nativo Intellij IDEIA Ultimate
  ``` /client/client.http```
    
