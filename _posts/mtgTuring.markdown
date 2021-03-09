---
layout: post
title:  "Welcome to Jekyll!"
date:   2021-03-03 15:17:21 -0300
categories: jekyll update
---

  Para posts como este:






 

Para quem quer uma resposta rapida:
Da para fazer um computador com as regras de Magic.

 

 Agora o porque:

Esse conceito de turing complete é altamente teórico e, francamente, desnecessario para a vida pratica. Entretanto é muito interressante que em 2019 tenha sido publicado este artigo

 
Magic: The Gathering is Turing Complete
de Alex Churchill, Stella Biderman, Austin Herrick

 

Neste post para ajudar o pessoal que, como eu, asdjfioasjifjasjdf

Pesquisei rapidamente e nao achei post sobre em portugues (mesmo tendo em ingles) e nao achei video sobre em portugues (mesmo tendo em ingles) .

 

Para explicar o que isso tudo fasdfassdfasfsdf

Abstract traduzido livremente:

 
Abstract — Magic: The Gathering é um evento popular e famoso complicado jogo de cartas colecionáveis ​​sobre combate mágico. 

 Bom não tenho que explicar o que é o MTG caso esteja lendo eu acho. Se não conheçe tem gente bem melhor que eu para fazer isso.
Neste paper, mostramos que o jogo ideal no mundo real do Magic é em menos tão difícil quanto o problema de parada, resolvendo um problema que está aberto há uma década. Para fazer isso, apresentamos um metodologia para incorporar uma máquina de Turing arbitrária em uma jogo de Magic de forma que o primeiro jogador tenha a garantia de ganhar o jogo se e somente se a máquina de Turing parar.

Primeiramente explicarei o que é uma maquina de turing. Sem entrar em detalhes, é como se fosse um computador mas teórico (ex, tem memória infinita). Digo, não é um computador como nenhum que você ja viu ou verá, é uma idéia. Dessa idéia todos os computadores (ou seja, para ser um computador deve ser uma derivação da maquina de turing, se não não é um computador (mesmo que pareça (video caso queria entender melhor))

Agora vamos falar de Turing Complete. Inicialmente, vejamos o que a wikipedia BR tem a dizer:

Na teoria da computação, um sistema de regras de manipulação de dados (como em um conjunto de instruções, uma -linguagem de programação, ou um autómato celular) é dito Turing-completo ou computacionalmente universal se e somente se puder ser usado para manipular qualquer máquina de Turing de única fita e assim, a princípio, qualquer computador. Um exemplo clássico é o cálculo lambda. A Turing-completude é assim denominada em memória a Alan Turing.

Na prática, Turing-completude significa que regras seguidas em sequência sobre dados arbitrários podem produzir o resultado de qualquer cálculo. Em linguagens procedurais isso poder ser satisfeito tendo-se, no mínimo, saltos condicionais (e.g., um "if" e um "goto") e a habilidade de modificar arbitrariamente locais da memória RAM (e.g., variáveis). Para mostrar que algo é Turing-completo, é suficiente mostrar que ele pode ser usado para simular o computador mais primitivo, pois mesmo o tipo mais simples de computador pode ser usado para simular os tipos mais complexos. Todas as linguagens de programação de uso geral e todos os conjuntos de instruções de máquina modernos são Turing-completos, não obstante limitações de memória finita.

Um computador universal é definido como um dispositivo com um conjunto de instruções Turing-completo, memória infinita, e um tempo de vida infinito. Todos os sistemas do mundo real necessariamente possuem memória finita, fazendo do verdadeiro computador universal apenas uma construção teórica.

Na teoria da computação, há um conceito bastante relacionado chamado de Turing-equivalência. Dois computadores P e Q são ditos Turing-equivalentes se P puder simular Q e Q puder simular P. Assim, um sistema Turing-completo é aquele que pode simular uma máquina de Turing. Porém, o termo é normalmente usado com o significado de Turing-equivalente a uma máquina de Turing. A razão é que qualquer máquina do mundo real pode ser simulada por uma máquina de Turing, observação esta codificada como a Tese de Church-Turing.

Um computador com acesso a uma fita infinita de dados é às vezes mais poderoso que uma máquina de Turing, pois a fita, a princípio, pode conter a solução para o problema da parada, ou para algum outro problema indecidível. Uma fita infinita de dados é chamada de Turing-oráculo. Até mesmo um Turing-oráculo com dados aleatórios não é computável (com probabilidade 1), pois há um número contável de computações, mas um número incontável de oráculos. Então, um computador com um Turing-oráculo aleatório pode computar coisas que uma máquina de Turing não pode. Uma máquina que é universal, exceto que não possui um Turing-oráculo, é chamada de máquina fracamente universal.

Para simplificar isso tudo, olha que comentarios fantasticos do StackOverflow (traduzidos livremente):

 

ere's the briefest explanation:

A Turing Complete system means a system in which a program can be written that will find an answer (although with no guarantees regarding runtime or memory).

So, if somebody says "my new thing is Turing Complete" that means in principle (although often not in practice) it could be used to solve any computation problem.

Sometimes it's a joke... a guy wrote a Turing Machine simulator in vi, so it's possible to say that vi is the only computational engine ever needed in the world.
Share
Improve this answer 

 

Alan Turing created a machine that can take a program, run that program, and show some result. But then he had to create different machines for different programs. So he created "Universal Turing Machine" that can take ANY program and run it.

Programming languages are similar to those machines (although virtual). They take programs and run them. Now, a programing language is called "Turing complete", if it can run any program (irrespective of the language) that a Turing machine can run given enough time and memory.

 answered May 16 '16 at 5:17
Raja Rao
4,48122 gold badges2222 silver badges27


Agora vou ou roubar uma explicação do Reddit que amei, abaixo tradução livre:

Uma linguagem de programação ou computador Turing Complete é aquele capaz de simular uma Máquina de Turing arbitrária. A Máquina de Turing era um computador hipotético proposto por Alan Turing.

Basicamente, se sua linguagem de programação tiver:

     se, então, senão

     vamos para

     matemática básica

     matrizes

então será Turing Completo. A barra de Completude de Turing não é uma barra particularmente alta para cruzar.

Um Arduino, uma calculadora gráfica TI-83 +, um Commodore C64 - todos são Turing Completos.

Embora uma máquina de Turing hipotética tenha uma quantidade infinita de memória, e nenhum computador real a tenha, a maioria das avaliações para saber se algo é realmente Turing completo tende a ignorar esse requisito.
Comentarios e conclusão:
 
"Nosso resultado se aplica de como o Magic real é jogado, pode ser alcançado usando decks legais de torneio padronizados e não depende de estocasticidade ou informações ocultas."
 
Jeito completo e bonito de dizer que da para fazer com cartas normais, "sem truques".
 
"Nosso resultado também é altamente incomum, pois todos os movimentos de ambos os jogadores são forçados na construção. "
 
Ou seja, jogando normalmente provavelmente esse resultado nunca vai acontecer (provavelmente...).
 
"Mostramos que mesmo reconhecendo quem vai ganhar um jogo em que nenhum o jogador tem uma decisão não trivial a tomar para o resto do jogo é indecidível. Concluímos com uma discussão sobre as implicações para uma teoria computacional unificada de jogos e observações sobre a jogabilidade de tal placa em um torneio."

 

 




 

 

 

https://oanic.medium.com/como-fazer-uma-magia-f44aa5e79edd

 

 


