---
layout: post
title: "Você sabe o que é Incompatibilidade de Impedância? - Banco de Dados Parte 1"
date: 2016-05-20 03:00:36 -0300
comments: true
categories: [Banco de Dados]
---

Ao se deparar com um termo estranho como "Incompatibilidade de Impedância" nos vem várias perguntas a mente: O que é isso? É contagioso? Será que é complicado? Por que devo me preocupar com isso?

Calma, calma! Vamos por partes...

Primeiro, vamos saber o que é essa tal de incompatibilidade de impedância.

A expressão "Incompatibilidade de impedância" ou "diferença de impedância" é uma expressão emprestada da engenharia elétrica que, de forma resumida, significa a diferença de resistência (carga resistiva) entre os componentes de um circuito.

Em engenharia de software este termo tem um significado um pouco diferente, ele simboliza a diferença entre o modelo relacional de dados, no caso de um banco de dados SQL como exemplo e o modelo orientado a objetos.

Como uma imagem vale mais que mil palavras, na figura abaixo fica clara a incompatibilidade de impedância entre as tabelas pedidos e itens do lado direito em relação ao objeto "pedido" a esquerda:

![tabela de pedidos](../images/pedido.png =500x)

Daí você deve estar pensando: -Tá, mas qual o problema nisso?

Existem diversos problemas associados a incompatibilidade de impedância, como o aumento do grau de complexidade da aplicação, dificultando ou simplesmente impossibilitando a manutenção da mesma, reduzindo drásticamente o tempo de vida útil da sua aplicação, ou simplesmente causando uma grande perda de performance devido a latência.

Desconhecer ou ignorar a diferença de impedância nas decisões iniciais de um projeto, pode lhe causar muitos problemas no futuro. Por isso, sempre leve em conta a diferença de impedância na escolha do seu modelo de banco de dados e das bibliotecas que você pretende utilizar para fazer a abstração desta comunicação.

No próximo artigo desta série, irei abordar técnicas para diminuir ou até eliminar a incompatibilidade de impedância da sua aplicação.

Se tiver qualquer dúvida, crítica ou sugestão, sinta-se à vontade para deixar um comentário :)