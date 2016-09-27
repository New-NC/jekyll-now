---
layout: post
title: Relatório semanal 01
---

Atividades realizadas na semana de 20 a 27 de setembro.

# Kanban

Nosso processo para este projeto é baseado em melhoria contínua, portanto nosso Kanban sofreu alterações nesta semana (e provavelmente sofrerá outras futuramente), para se adequar ao que estamos aprendendo enquanto realizamos o projeto.
As tasks serão melhor organizadas nesta semana, colocando prioridades e datas de entrega.

# Atividades escolhidas

As três atividades puxadas do backlog da Sprint 1 foram: preparação do ambiente de desenvolvimento da API, aprendizado da API, e início da lógica para busca nas resenhas.

# Padrões SOLID

Após realizar o treinamento em confiança do código, decidimos usar o padrão SOLID no projeto. Por isso estamos trabalhando com interfaces e herança, e classes com responsabilidade única.

# Padrão Factory

Para a criação do objeto com as informações do filme estamos utilizando arquivo JSON. Porém, como queremos um código fechado para modificação e aberto para extensão criamos uma classe baseando-se no padrão factory.
Essa classe `ObjectFactory` estabelece um contrato de criação com a classe que a implementa, que está atrelada ao tipo de arquivo de entrada (JSON, xml, entre outros).

# Atualização do idioma usada no código

Refatoramos o código para usar nomes de classe, variáveis e métodos em inglês.
