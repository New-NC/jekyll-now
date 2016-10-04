---
layout: post
title: Relatório semanal 02
---

Atividades realizadas na semana de 27 a 04 de outubro.


# Definição de labels

Para a primeira fase de IHC, nós utilizamos um questionário para entender melhor o nosso público alvo. Nele, uma das perguntas era: "O que você mais gosta no mundo?". Com as respostas, criamos labels para buscas nas resenhas. Uma das nossas telas fará essa mesma pergunta ao usuário e, ele poderá digitar a resposta ou escolher uma dessas labels pré-definidas.
Elas são: Game/Play; Family; Food; Tech; Anime; Internet; Computer; Travel; Minecraft; Pokémon; Friend; Science; Music; Book; Nature; Candy/candies.


# Busca nas resenhas

Nós definimos que a busca nas resenhas será feita por sub-string, assim quando buscarmos por game, teremos resenhas com videogames, games e game, por exemplo. Durante a busca guardam-se as labels e no fim classifica-se cada filme de acordo com as labels mais presentes nele, para permitir encontrá-lo com facilidade durante a aplicação do questionário.


# Problema Parse JSON

Quando refatoramos o código, fizemos uma mudança de nome em um campo da classe responsável por manter as informações do filme, por isso tivemos um problema com campos nulos. Os nomes das variáveis na classe MovieInfo precisam ser idênticos aos campos do JSON, na solução que escolhemos. Demoramos um tempo até descobrir que o problema era esse, mas agora já está resolvido.


# Repositório de filmes

Decidimos guardar os filmes que são requisitados para serem pré-classificados em memória, em vez de usar um banco de dados, já que os filmes serão constantemente atualizados e os procedimentos aplicados sobre eles precisam ser rápidos.


# Timer para atualização dos objetos

Nosso servidor mantém uma lista de filmes classificados segundo as labels de busca, isso é feito inicialmente e atualizado de acordo com o *timer* que foi implementado, a cada hora.
