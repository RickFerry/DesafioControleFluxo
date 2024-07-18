```markdown
# Desafio Controle de Fluxo

Este projeto é uma aplicação Java simples que demonstra o controle de fluxo em Java, utilizando exceções personalizadas para validar parâmetros de entrada. O objetivo é fornecer um exemplo prático de como lançar e tratar exceções em Java, além de praticar a estruturação de código e refatoração.

## Funcionalidades

- Solicita ao usuário dois parâmetros numéricos via terminal.
- Valida os parâmetros para garantir que o primeiro seja menor que o segundo.
- Caso os parâmetros sejam válidos, imprime todos os números inteiros entre eles (inclusive).
- Caso os parâmetros sejam inválidos, lança uma exceção personalizada e informa o usuário sobre o erro.

## Tecnologias Utilizadas

- Java 17
- Maven

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- `src/main/java/com/study/Contador.java`: Contém a lógica principal do programa, incluindo a solicitação de entrada do usuário, validação dos parâmetros e impressão dos números.
- `src/main/java/com/study/exception/ParametrosInvalidosException.java`: Define uma exceção personalizada utilizada para indicar que os parâmetros de entrada não são válidos.
- `pom.xml`: Arquivo de configuração do Maven, especificando as dependências e a versão do Java utilizada.

## Como Executar

Para executar este projeto, você precisará ter o Java e o Maven instalados em sua máquina. Siga os passos abaixo:

1. Clone o repositório para sua máquina local.
2. Abra um terminal na pasta raiz do projeto.
3. Execute o comando `mvn clean install` para compilar o projeto e criar o arquivo `.jar`.
4. Execute o comando `java -jar target/DesafioControleFluxo-1.0-SNAPSHOT.jar` para iniciar a aplicação.

## Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
```
