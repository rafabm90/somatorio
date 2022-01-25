# Somatório

Uma função que recebe um número inteiro positivo e retorna o somatório de todos os valores inteiros divisíveis por 3 ou 5 que sejam inferiores ao número passado.

## Começando

Para rodar o projeto localmente é necessário que tenha o dart instalado.

### Instalando no Windows

Para a instalação no Windows precisamos primeiramente instalar o chocolatey que é, basicamente, um gerenciador de pacotes, após sua instalação abra o o cmd do Windows em modo administrativo e rode o seguinte comando: 

```
choco install dart-sdk
```

### Instalando no Linux

Para a instalação no Linux, precisamos do pacote **apt-transport-https** para permitir que pacotes sejam baixos via https. Para isso, no terminal do  linux, utilize os seguintes comandos:

```
sudo apt-get update
 sudo apt-get install apt-transport-https
 sudo sh -c 'wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -'
 sudo sh -c 'wget -qO- https://storage.googleapis.com/download.dartlang.org/linux/debian/dart_stable.list > /etc/apt/sources.list.d/dart_stable.list'
 ```

 Agora, com os pacotes ja baixados, basta instalar o dart, utilizando os seguintes comandos:

 ```
 sudo apt-get update
 sudo apt-get install dart
 ```

 ## Executando nosso código

 Para executarmos nosso código precisaremos de um editor de texto, para códigos em dart recomendo o Visual Studio Code ou o Android Studio, com a IDE escolhida e ja instalada vamos clonar o repositório para rodar o código localmente, para isso abra o git na pasta desejada e rode o seguinte comando: 

 ```
 git clone https://github.com/rafabm90/somatorio.git
 ```

 Com o projeto em sua máquina, abra o terminal onde o projeto se econtra e rode o seguinte comando:

 ```
 dart run main.dart
 ```

Dessa forma, você é capaz de rodar o projeto localmente e pode ser capaz de visualizar os resultados obtidos pelo terminal

## Extra

Caso queira testar outros numeros, edite o codigo main e faça mais requisiçoes da funçao somatório e print o resultado retornado.