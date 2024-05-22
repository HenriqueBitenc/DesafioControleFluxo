# Contador de Parâmetros

Este projeto é uma aplicação Java que solicita dois parâmetros ao usuário e realiza uma contagem com base nesses parâmetros. Se o primeiro parâmetro for maior que o segundo, uma exceção personalizada é lançada.

## Estrutura do Projeto

O projeto é composto por duas classes Java:

- **Contador.java**: Contém a lógica principal da aplicação, incluindo a solicitação de parâmetros, a contagem e o tratamento de exceções.
- **ParametrosInvalidosException.java**: Define uma exceção personalizada para lidar com parâmetros inválidos.

## Funcionalidades

- **Solicitação de Parâmetros**: Solicita dois números inteiros ao usuário.
- **Contagem**: Realiza uma contagem do primeiro parâmetro até o segundo, imprimindo cada número.
- **Tratamento de Exceções**: Lança uma exceção personalizada se o primeiro parâmetro for maior que o segundo, e solicita os parâmetros novamente.

## Intuito Teórico

Este projeto foi desenvolvido com *intuito teórico* e para *fins de estudo*. Ele serve como um exemplo prático de como implementar contagem simples em Java e como lidar com exceções personalizadas. Para alterar as funcionalidades, as modificações devem ser feitas diretamente nas classes `Contador.java` e `ParametrosInvalidosException.java`.

## Como Executar no VS Code

1. Certifique-se de ter o [Visual Studio Code](https://code.visualstudio.com/) instalado.

2. Certifique-se de ter o [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) instalado.

3. Clone este repositório ou baixe os arquivos do projeto para uma pasta local.

4. Abra o Visual Studio Code e a pasta onde os arquivos estão localizados.

5. No VS Code, instale a extensão [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) se ainda não estiver instalada.

6. Abra o arquivo `Contador.java`.

7. Compile e execute o arquivo usando os comandos do VS Code. Você pode clicar com o botão direito do mouse no editor de código e selecionar `Run Java` ou usar o atalho `Ctrl+F5`.


---

Este README foi gerado com *auxílio de uma IA*.
