---
layout: post
title: Relatório semanal 09
---

Atividades realizadas na semana de 16 a 22 de novembro.


# Implementação da terceira tela de pergunta
Finalizamos a implementação da lógica da terceira tela de pergunta, tanto por parte
da aplicação como de nosso API. Assim como temos um repositório para filmes recentes
e mais bem avaliados, temos para os filmes agrupados por estúdios pré-definidos.

# Recuperação e exibição dos detalhes de um filme
Implementamos a lógica dessa tela de fato, onde através do id de um filme fazemos
uma requisição para o TMDB API e recuperamos informações como o título do filme,
data de lançamento, votos médios, sinopse e sua imagem de capa.

# Login com o Facebook
Implementamos o login com o Facebook em nossa aplicação, porém precisamos realizar
mais implementações me questão de interface para usarmos essa nova feature de fato.

# Preparo da aplicação e API para experimento de IHC
A nova versão da API foi implantada no Heroku, o APK da aplicação android também foi
gerado para que a equipe de IHC possa realizar seus experimentos. A aplicação como um
todo contempla todas as telas desenvolvidas e funcionais até então, apenas não possuindo
ainda integração com o Facebook.
