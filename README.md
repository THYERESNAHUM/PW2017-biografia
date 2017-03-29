## Repositorio para Atividades

**Disciplina**

Programação para Web 2017-1

**Link para repositorio**

https://github.com/THYERESNAHUM/PW2017-biografia.git

**Procedimento para clonar o repositorio**
```
git clone https://github.com/THYERESNAHUM/PW2017-biografia.git
```
**Comando para executar o servidor Tomcat**
```
mvn org.apache.tomcat.maven:tomcat7-maven-plugin:run
```
**Para Acessar Biografia**

http://localhost:8080/biografia em qualquer navegador.

Caso esteja clonando o repositorio no Linux, use ./mvn ao invés de apenas mvn, como no Windows. Além disso, pelo menos uma vez, é preciso dar permissão de execução ao arquivo de script mvn com o comando chmod +x mvn.

**Observação**

Substitua o comando **mvn** por **mvnw** caso seja exibida a mensagem de comando não encontrado

**Para "empacotar" a aplicação**
```
mvnw package
```
 
**Caso queira compactar o pacote para executar em maquinas sem maven instalado.**
```
mvn io.takari:maven:0.3.3:wrapper -Dmaven=3.3.9
```
