# Golang Completo e Total

Esse repo contém o material de apoio para o curso __GoLang Completo e Total__

## Instalação das Ferramentas

Para instalar o compilador e ferramentas do GoLang, basta fazer o download da versão apropriada ao
seu sistema operacional no seguinte caminho: [Download GoLang](https://go.dev/dl/)

Caso utilize o VSC, é recomendável instalar a seguinte extenção:
[Go for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=golang.go)
Essa extensão recursos de ênfase para a sintaxe, auto-complete para o código, preenchimento
automático dos pacotes de dependências, navegação fácil por todo o código, diagnóstico, sugestões,
debug e testes.

Existem algumas alternativas para testar códigos em GoLang online:

- [OneCompiler](https://onecompiler.com/go)
- [myCompiler](https://www.mycompiler.io/new/go)
- [OnlineGDB](https://www.onlinegdb.com/online_go_compiler)

## Programa Hello World

O tradicional programa para imprimir uma mensagem de "Hello World !" está disponível na pasta
[helloWorld](https://github.com/aldebap/go_completo_total/tree/main/helloWorld).
Para executar esse programa diretamente a partir da linha de comando, utilizar o seguinte:

```sh
go run main.go
```

## Sintaxe de GoLang

A pasta __sintaxe__ contém os programas utilizados para demonstrar os detalhes da sintaxe de GoLang.
Dentro dessa pasta, existe uma sub-pasta para cada aspecto da sintaxe de GoLang tratada no cusso:

- [comentarios](https://github.com/aldebap/go_completo_total/tree/main/sintaxe/01_comentarios)
- [literais](https://github.com/aldebap/go_completo_total/tree/main/sintaxe/02_literais)
- [constantes](https://github.com/aldebap/go_completo_total/tree/main/sintaxe/03_constantes)
- [variaveis](https://github.com/aldebap/go_completo_total/tree/main/sintaxe/04_variaveis)

TODO: corrigir todos os links

- [arrays](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/arrays)
- [slices](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/slices)
- [maps](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/maps)
- [ponteiros](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/ponteiros)
- [condicoes](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/condicoes)
- [lacos gerais](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/lacos%20gerais)
- [lacos sobre arrays](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/lacos%20sobre%20arrays)
- [lacos sobre maps](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/lacos%20sobre%20maps)
- [funcoes](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/funcoes)
- [parametros de funcoes](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/parametros%20de%20funcoes)
- [retorno de funcoes](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/retorno%20de%20funcoes)
- [valor de funcoes](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/valor%20de%20funcoes)
- [tratamento de erros](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/tratamento%20erros)
- [go functions](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/go%20functions)
- [estruturas](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/estruturas)
- [metodos](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/metodos)
- [interface](https://github.com/aldebap/Masterclass_Golang/tree/main/sintaxe/interface)

## Programa Hello API

Hello API é uma versão REstFul API do programa para imprimir uma mensagem de "Hello World !" e está
disponível na pasta [helloAPI](https://github.com/aldebap/Masterclass_Golang/tree/main/helloAPI).
Para executar esse programa diretamente a partir da linha de comando, utilizar o seguinte:

```sh
go run main.go
```

Como um API é um servidor web, ele escuta requisições na porta 8080, e para ser encerrado é preciso
utilizar o sinal CTRL + C para interromper o servidor.
Na pasta [test](https://github.com/aldebap/Masterclass_Golang/tree/main/test) existe uma coleção
para o [Postman](https://www.postman.com/) que permite testar o Hello API utilizando uma requisição
na pasta __Hello API__ da coleção.
