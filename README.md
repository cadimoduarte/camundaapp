## 1. Requisitos
Para executar o projeto é necessária a instalação das seguintes ferramentas:

```
1. JDK 1.8
2. Maven 3 (ou superior)
3. Docker 17.06 (ou superior)
4. Docker Compose 1.14  (ou superior)
```

## 2. Alterações
Além disso, para realizar o desenvolvimento e testes será preciso:
```
1. IDE ( eclipse ou intellij )
3. Camunda modeler
4. Postman
```


## 3. Executando o Projeto
Para executar o projeto é preciso subir os serviços docker

````
$ cd docker
$ docker-compose -f docker-integration up
````

Uma vez com o docker-compose em execução, o projeto pode ser executado via bash ou dentro de uma IDE.
Para executar via bash:

```
$ java -jar workflow-engine/target/workflow-engine-1.0-SNAPSHOT.jar
```
