# Docker e Docker Compose


## O que é Docker?
O Docker é uma ferramenta que serve para fechar o nosso sistema dentro de um "container" isolado. A grande vantagem dele é que o programa roda igual em qualquer computador, sem aquela desculpa de que "na minha máquina funciona e na sua não", e de um jeito muito mais leve do que usar uma máquina virtual inteira.

## Imagem vs Container
A imagem é o molde, como se fosse um instalador de jogo ou uma receita de bolo (você não consegue mexer nela, ela só serve de base). Já o container é esse molde funcionando na prática, ou seja, é o jogo aberto e rodando na tela onde você pode jogar e mexer nas coisas.

## O que é um Dockerfile?
O Dockerfile é um arquivo de texto onde você escreve a receita para criar a sua própria imagem. Nele você coloca comandos simples como: "pegue o Windows/Linux de base", "copie a pasta do meu projeto para dentro" e "instale o programa X". O Docker lê isso e monta tudo sozinho.

## O que é Docker Compose?
Quando um projeto precisa de várias coisas rodando juntas (tipo um site, um banco de dados e um chat), em vez de ligar um por um na mão, você usa o Docker Compose. Ele usa um arquivo (docker-compose.yml) para listar todos esses containers e, com um único comando, liga e conecta todo mundo de uma vez só.

## Exemplo Prático
Na vida real, a gente cria o código do nosso site, escreve o Dockerfile para transformar esse site em uma imagem e depois usa o Docker Compose para fazer esse site conversar certinho com o banco de dados.

#Referencias
https://docs.docker.com/get-started/docker-overview/
https://docs.docker.com/get-started/docker-overview/#images-and-containers
https://docs.docker.com/reference/dockerfile/
https://docs.docker.com/compose/
https://docs.docker.com/compose/gettingstarted/
