---
share: true
title: Introdução à Arquitetura de Software
date: 2024-06-09

filename: 2024-06-09-arquitetura-software-introducao
layout: post
---

Abordaremos aqui os conceitos relativos à área da Arquitetura de Software, tendo como objetivo principal contextualizar o assunto através da explanação de temas que compõem o estudo e as aplicações deste ramo.

\
**Definição**

Ao que parece, a estrutura de software se dá pouco a intuição desenvolvida sobre os aspectos de, por exemplo, a estrutura de um prédio; onde a estrutura física é, de certa forma, óbvia: em concreto armado, lajes, vigas e pilares. Essas estruturas estão para os limites impostos pela consequência da geometria do espaço-tempo (a gravidade), proposta por Albert Einstein. O software está pouco para a gravidade. Softwares robustos são compostos por “componentes de software menores, que, por sua vez, são formados por componentes ainda menores de software, e assim por diante. É um código dentro do outro, do início ao fim.” (ROBERT, 2018). 
Portanto, apesar de poder ser difícil confirmar ou compreender a estrutura bruta de vários softwares, é de extrema importância lembrar que se a arquitetura for negligenciada a medida das outras “preocupações” que se tem para produzir um software de qualidade — como, por exemplo, os recursos e funções do domínio da aplicação — serão justamente esses recursos e funções que se tornarão difíceis de serem desenvolvidos, manuteníveis e ampliados à medida da crescente demanda requerida pelo domínio da aplicação e/ou pelo próprio mercado de software.
“A arquitetura é o conjunto de decisões que você queria ter tomado logo no início do projeto, mas, como todo mundo, não teve imaginação necessária.” — Ralph Johnson.
Pode-se então delimitar o conceito de arquitetura de software como sendo: “uma disciplina que busca definir a estrutura geral do software, incluindo a divisão em módulos, a comunicação entre eles e os padrões de interação com o usuário.” (ROBERT, 2019).
“A arquitetura representa as decisões significativas de design que moldam um sistema, onde a significância é medida pelo custo da mudança.” — Grady Booch.

\
**O propósito da Arquitetura**

Como descrito no tópico anterior, a arquitetura de software está pouco para a intuição desenvolvida sobre os aspectos de um prédio, como, por exemplo, a força imposta pela gravidade. Mas há um ponto onde as duas áreas compartilham uma única ideia: o mantenimento da funcionalidade. Não é comum observar hordas de trabalhadores dando manutenção em uma construção civil para manter ela em pé e funcionando, os defeitos surgem, em boa parte, por conta da simples passagem do tempo — com base na Lei da Entropia. 
Nesse mesmo aspecto, não deveria ser comum observar hordas de programadores trabalhando sobre sistemas para mantê-los “em pé” e funcionando adequadamente. Para que esse mantenimento ocorra sem a “força bruta” e incontáveis programadores, deve ser proposto uma cultura que vá além da “força de vontade” e parta para um grau de raciocínio aprofundado, disciplina e dedicação nas quais a maioria dos desenvolvedores de software não está disposto a construir, dia a dia e repetidamente.
Quando esse raciocínio aprofundado sobre o software não é abdicado, o esforço humano é atenuado e a funcionalidade e flexibilidade são estimuladas, ou seja, tempo, dinheiro e esforço dão sentido de escala para parametrizar os fatores que são importantes e/ou urgentes dos que não são.

Ivar Jacobson argumenta que as arquiteturas de softwares são estruturas que suportam os casos de uso do sistema, ou seja, eles devem deixar estritamente explícito o domínio de uma aplicação. Pode-se então avaliar que, por exemplo, o uso limitado a frameworks para construção da arquitetura do software vai de encontro com os casos de uso de cada aplicação.
Em paralelo a essa abordagem, a garantia da construção de uma casa com base em tijolos não é tida, em primeira instância, como essencial, mas a preocupação maior inicialmente é garantir que a casa seja ao menos utilizável para seu propósito. 
Portanto, as boas arquiteturas devem ser centradas em casos de uso para que os arquitetos possam descrever com segurança as estruturas que suportam esses casos de uso, sem se comprometerem com frameworks, ferramentas e ambientes. (ROBERT, 2018).  Logo, identificar a melhor arquitetura para determinado sistema de software, dependendo das necessidades e dos requisitos temporais do sistema em questão, pode garantir o sucesso de um projeto.

\
### Referências

BRUNO, R. C. Arquiteturas e Padrões de Projeto no Desenvolvimento de Software: Uma Análise Comparativa e Quantiva. 2023. Disponível em: [Meu Drive pessoal.](https://drive.google.com/file/d/1BBEyQYH-4xGppTguzkogAvD6wqnp-1JJ/view?usp=sharing)