---
layout: post
title: Relatório semanal 02
---

Atividades realizadas na semana de 27 a 04 de outubro.

# Definição de labels

Para a primeira fase de IHC, nós utilizamos um questionário para entender melhor o nosso público alvo. Nele, uma das perguntas era: "O que você mais gosta no mundo?". Com as respostas, criamos labels para buscas nas resenhas. Uma das nossas telas fará essa mesma pergunta ao usuário e, ele poderá digitar a resposta ou escolher uma dessas labels pré-definidas.
Elas são: Game/Play; Family; Food; Tech; Anime; Internet; Computer; Travel; Minecraft; Pokémon; Friend; Science; Music; Book; Nature; Candy/candies.


# Busca nas resenhas

Nós definimos que a busca nas resenhas será feita por sub-string, assim quando buscarmos por game, teremos resenhas com videogames, games e game, por exemplo.

# Problema Parse JSON

Quando refatoramos o código, fizemos uma mudança de nome em um campo da classe responsável por manter as informações do filme, por isso tivemos um problema com campos nulos. Os nomes das variáveis na classe MovieInfo precisam ser idênticos aos campos do JSON, na solução que escolhemos. Demoramos um tempo até descobrir que o problema era esse, mas agora já está resolvido.

# Repositório de filmes

# Busca por labels
