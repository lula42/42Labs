# O mini-guia quase definitivo sobre as cerimônias do mão-na-massa
*versão: mao-na-massa.md-v0.2*

Olá, cadete! Se você está lendo isso, provavelmente faz parte ou pretende fazer parte do 42Labs, e está buscando mais informações sobre como funciona a parte do mão-na-massa do 42Labs.

Antes de tudo, é importante ter em mente que não usamos um só método ou framework. Desde o Setup já começamos a praticar bastante do [Extreme Programming - XP](https://www.agilealliance.org/glossary/xp), e durante o mão-na-massa estamos colocando no nosso cinturão de utilidades também práticas do [Scrum](https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-PortugueseBR-2.0.pdf).

Entender sobre a essência desses métodos vai sempre te ajudar a compreender os caminhos que estamos tomando, e colaborar para a melhoria contínua. Mas esse mini-guia já é um bom próximo passo nessa jornada.

## Cerimônias

Durante o mão-na-massa, o que a gente mais pega do Scrum são as cerimônias. Essas reuniões, que acontecem dentro de um período fixo e pré-estabelecido, garantem a cadência necessária para evolução e adaptação tanto do nosso produto quanto do nosso time.

Todas as cerimônias fazem parte de um Sprint, que é um período de tempo (no nosso caso de 2 semanas) em que perseguiremos juntos um objetivo para a evolução do nosso produto.

Antes de detalhar cada cerimônia é importante trazer uma dica de ouro:

*Para não virar uma grande bagunça, é legal antes de cada reunião já termos definido quem será a pessoa que facilitará a reunião. A pessoa que será mestre de cerimônias, sabe? Responsável por conduzir os participantes da reunião rumo ao objetivo. Inclusive, **é altamente recomendável que essa mesma pessoa leia esse mini-guia antes da cerimônia**. Nos anexos deste documento você encontra mais sobre [Facilitação](#facilitação) e sobre [Como escolher quem vai facilitar](#como-escolher-quem-vai-facilitar)*

Nessa seção você encontra um [Resumão compilado de cada cerimônia](#resumão-compilado-de-cada-cerimônia), [Perguntas úteis em cada cerimônia](#perguntas-úteis-em-cada-cerimônia) e [Anti-padrões de cada cerimônia](#Anti-padrões-de-cada-cerimônia).

### Resumão compilado de cada cerimônia

- **Refinamento**
	- Duração: de 1 a 2 horas
	- Ocorre: No meio do Sprint atual, para planejar o próximo Sprint
	- Participantes: Qualquer pessoa que esteja pensando no futuro do produto
	- Objetivo: Organizar o backlog do produto (possíveis itens a serem desenvolvidos), deixando-o tão preparado quanto possível para a próxima Planning

- **Planning**
	- Duração: 1 hora
	- Ocorre: No começo do Sprint
	- Participantes: O time de desenvolvimento e qualquer pessoa interessada que possa contribuir
	- Objetivo: Definir o nosso objetivo para as próximas duas semanas, decidir com quais itens do backlog nos comprometeremos para essas duas semanas e quebrar cada um deles em tarefas técnicas

- **Review**
	- Duração: 1 hora
	- Ocorre: No final do Sprint, antes da Retrospectiva
	- Participantes: O time de desenvolvimento, pessoas interessadas e pessoas parecidas com as nossas personas que possam dar feedbacks sobre o produto que desenvolvemos
	- Objetivo: Mostrar o produto funcionando e coletar feedbacks sobre ele. Atenção: sem relatar o que ocorreu durante a sprint, sem dar desculpas ou justificativas para o produto estar como está e sem se comprometer com desenvolvimentos futuros

- **Retrospectiva**
	- Duração: 1 hora
	- Ocorre: No final da Sprint, entre a Review e a próxima Planning
	- Participantes: O time de desenvolvimento e qualquer pessoa que possa contribuir para a evolução do time
	- Objetivo: Refletir sobre como podemos ficar mais efetivos para o próximo Sprint enquanto time

### Perguntas úteis em cada cerimônia

- **Refinamento**
	1. Existe alguma coisa na nossa área de refinamento do Miro que já não faz mais sentido para o nosso futuro (ou por já ter sido feito ou por ter ficado obsoleta) e que a gente pode apagar?

	2. As features (que vieram lááá do sequenciador de features) que estão atualmente na nossa área de refinamento (objetivos vs personas) ainda "dão suco" ou já esprememos (fatiamos) o suficiente para entender elas como completas e tirar do nosso quadro de refinamento?

	3. As features que permanecem no nosso quadro são suficientes para trabalharmos atualmente dada a visão que temos para as próximas semanas ou deveríamos puxar alguma outra do sequenciador de features (ou de qualquer outro lugar)?

	4. Quais fatias podemos extrair de cada uma das features posicionadas no quadro afim de ajudar a persona a alcançar um objetivo?

	5. A quantidade de features que extraimos é suficiente/mais que suficiente para o próximo sprint?

- **Planning**
	1. Quais das histórias já fatiadas são mais prioritárias para puxarmos para esse Sprint? (De forma ordenada da mais importante para a menos importante)

	2. Existe algum feedback simples da Review que já possamos considerar como uma nova história a ser feita nesse Sprint? (Feedbacks sobre os quais ainda precisamos pensar ficam para o próximo refinamento; Introduzir essas histórias mais simples dentro da lista de prioridades da questão 1)

	3. Todas as histórias têm como foco atender alguma necessidade de uma das nossas personas? (Se não tiver, provavelmente não é uma história, é só uma task dentro de outra história)

	4. Esse número de histórias que puxamos é suficiente para o próximo Sprint?

	5. História a história: quais as tarefas técnicas que precisamos fazer para desenvolver essa história? (Colocar as tasks dentro do card da história)

- **Review**
	1. As pessoas que não fazem parte do time (de preferência alguém que esteja muito próximo ao nosso consumidor real/persona) viram o produto em funcionamento?

	2. Quais feedbacks essas pessoas têm para nos dar?

	3. Elas usariam o nosso produto da forma como ele está atualmente?

	4. Quais necessidades delas o nosso produto resolve?

	5. Temos feedbacks (insumos) o suficiente para o próximo refinamento?

- **Retrospectiva**
	1. Quais são os problemas atuais na performance do nosso time que precisamos resolver?

	2. O que nos impede de trabalhar ainda melhor?

	3. Como estão nossas métricas? O que elas nos dizem?

	4. O que podemos/devemos celebrar, enquanto time?

	6. Quais são as ações para ficarmos melhor para o próximo Sprint, e quem está responsável por puxar cada uma delas?

### Anti-padrões de cada cerimônia

- **Refinamento**
	1. O time refina novas histórias mas não se prepara para executá-las. Caso os integrantes tenham dúvidas muito grandes sobre como implementar determinada feature, a solução deve ser pesquisada e estudada ANTES que a feature possa ser selecionada em um planning.

	2. O refinamento dura muito menos do que o agendado. Um refinamento grosseiro ou mal feito pode levar a atrasos e dificuldades no planning e sprint seguintes. O tempo sobressalente de um refinamento pode ser usado para pesquisa e estudo conforme o item acima.

	3. O time se esquece do feedback recebido. No início do refinamento vale a pena reler o feedback recebido para adaptar ou criar novas histórias de acordo com as informações obtidas durante um review.

- **Planning**
	1. O time seleciona uma história que possui um alto grau de incerteza. Evite selecionar histórias em que não se conhece o tamanho ou a complexidade de um problema. Na dúvida, não selecione a história e estude-a ao longo do sprint, para então selecioná-la no próximo planning.

	2. O time cria muitas novas features logo após receber feedback. Pequenos recursos ou modificações podem ser adaptados durante o planning, mas guarde tarefas maiores para o refinamento onde novas features podem ser discutidas com mais tempo para conversa e estudo.

- **Review**
	1. O time faz um status report. Esta não é a hora de discutir o que foi feito e o que deixou de ser feito. O review serve para coletar feeback sobre o produto.

	2. O time se justifica por não entregar determinada feature. O momento de discutir os motivos de atrasos ou dificuldades é durante a retrospectiva.

	3. O time faz um comprometimento prematuro. Recebido o feedback, o time se compromete a entregar determinada feature que até então não estava planejada. Novas história devem ser discutidas, possivelmente estudadas, e só então selecionadas.

	4. O time não faz perguntas. Em muitos casos, uma das pessoas envolvidas no review terá um perfil muito próximo a uma das personas usuárias do seu projeto. Essa é a hora de conhecer suas opiniões e necessidades reais no que se refere ao produto.

	5. O time não faz anotações. Anote tudo o que puder e que for relevante. O feedback é valioso e não deve ser esquecido, mesmo que acabe não sendo implementado.

- **Retrospectiva**
	1. O time não se compromete com as ações discutidas. Ao final da retrospectiva, cada membro do time deve se voluntariar para desempenhar determinadas ações que melhorarão o próximo sprint. Uma ação pode ter mais de um responsável.

# Anexos

## Facilitação

Segundo [o livro A Arte da Facilitação](https://leanpub.com/aartedafacilitacao/c/cupom-agile-pub):

> Independente do formato de trabalho, qualquer encontro sem foco e objetividade impacta negativamente as organizações e seus negócios, pois desacelera o processo de adaptação em resposta às mudanças que o mercado impõe. Partindo dessa premissa, conduzir uma reunião torna-se algo mais complexo. Existe uma série de fatores que podem influenciar o seu resultado de maneira positiva ou negativa e todo esse contexto só aumenta a responsabilidade da pessoa facilitadora e a necessidade da facilitação. Sendo assim, urge um aprofundamento no entendimento desse tema. Primeiramente, é preciso entender o que é facilitação. Michael Wilkinson (2004) definiu esse ponto da seguinte forma:
>
> “Uma reunião altamente estruturada em que o líder da reunião (a pessoa facilitadora) orienta os participantes por uma série de etapas predefinidas para chegar a um resultado que seja criado, compreendido e aceito por todos os participantes.”
>
> A facilitação existe para organizar a forma como as reuniões devem ser conduzidas e ajudar os participantes chegarem a um resultado. Ter essa premissa é importante para uma melhor compreensão da atuação da pessoa facilitadora.

Um dos objetivos da 42 é formar Human Coders. No 42Labs, mais do que nunca, isso é levado a sério: Habilidades complementares à programação são desenvolvidas o tempo todo. De User Experience a Facilitação.

### Como escolher quem vai facilitar

A forma mais simples de escolher quem vai facilitar a reunião é, talvez, vendo se alguém se voluntaria para facilitar.

Uma outra opção talvez seja fazer uma votação simples:

- Alguém explica o que é facilitação
- Pergunta-se quem são os candidatos a facilitar
- Todos votam pelo chat (não só nos candidatos, mas em todos os presente)
- A pessoa que tiver mais votos é denominada facilitadora

Se você quiser algo sutilmente mais rebuscado, uma votação em 2 turnos pode ser uma boa ideia:

- Depois do primeiro turno, cada pessoa justifica porque votou em quem votou
- Os votos do primeiro turno são descartados, e faz-se uma nova votação
- A pessoa que tiver mais votos neste segundo turno é denominada facilitadora
