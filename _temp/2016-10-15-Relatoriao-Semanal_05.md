---
layout: post
title: Relatório semanal 04
---

Atividades realizadas na semana de 11 a 18 de outubro.


# Segunda tela de pergunta
O aplicativo terá várias telas de perguntas, para o MVP1 iremos entregar 2. A primeira já havia sido implementada na semana passada, porém as capas estavam estáticas. Nessa semana, o protótipo da segunda tela foi feito e então, pudemos fazer o seu código. Nela temos 4 capas, cada tela corresponde a uma label: animal, tecnologia, princesa e aventura.

# Tela de resultados
A tela de resultados mostra 5 filmes, com base nas respostas das perguntas anteriores. Para navegar entre os filmes utilizamos o scroll, já que a quantidade de filmes é limitada. Ao finalizar, o usuário tem a opção de retornar a tela inicial.

# Botão Home/Next
Para não poluirmos a interface decidimos ter um mesmo botão para retornar a página inicial ou para ir para próxima questão. Se nenhuma capa de filme foi escolhida, o usuário verá a opção Home. Ao escolher uma capa, o botão será o Next e não mais Home.
Mudamos, também, a função do botão return do celular. Se clicado, ele não voltará a pergunta anterior, e sim a tela inicial(home).

# Código do Servidor (back-end)
O back-end possuía uma classe repositório para os filmes, agora são dois repositórios derivadoes deste, um para filmes mais bem avaliados, outro para filmes mais novos. E ambos possuem listas de filmes separados pelas categorias: animal, princesa, tecnologia, e aventura.
Essas listas são populadas por filmes de acordo com os rótulos (*labels*) que cada filme recebe no classificador (por resenhas e título).

Nas duas primeiras semanas desta sprint o back-end foi desenvolvido, testado e se apresentou funcional, na terceira e início da quarta semana o aplicativo foi desenvolvido, testado estaticamente e também se apresentou funcional, porém nesta semana quando fomos ligando as funcionalidades do servidor(back-end) ao aplicativo algumas delas apresentaram problemas difíceis de serem encontrados, o que consumiu mais tempo do que o previsto para essas atividades.

Entretanto, tivemos problemas quanto a recuperar esses rótulos, existiam bugs de lógica que acabavam não encontrando as *labels* mas mesmo assim populando as listas com elementos vazios. 
Este problema demorou para ser encontrado e atrasou o desenvolvimento tanto da segunda tela de pergunta quanto da tela de resultados, já que optamos por refazer as partes do código que apresentavam problemas. E essa reimplementação causou problemas menores que não esperávamos.
