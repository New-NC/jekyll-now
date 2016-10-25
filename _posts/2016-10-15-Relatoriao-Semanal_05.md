---
layout: post
title: Relatório semanal 05
---

Atividades realizadas na semana de 18 a 25 de outubro.


# Resolução do problema das labels
O bug foi encontrado dentro do OverviewSearcher, onde estavámos atribuindo a lista de labels a um filme.

# Listener para atualização do repositório
Na inicialização da API, criamos um listener para a criação/atualização do nosso repositório de filmes.

# Lista de palavras não desejadas no filme
Criamos uma lista de palavras ruins, assim filmes que as contém não são adicionados as nossas listas personalizadas.

# Simplificação da alimentação das listas de categorias
Refatoração do código para seguir melhor as práticas de orientação a objetos no quesito de herança.

# API hospedada no Heroku
Com a melhora no código, diminuímos significativamente o tempo para receber os filmes, então resolvemos o problema de time-out que tínhamos ao tentar usar o Heroku.