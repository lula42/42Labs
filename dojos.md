# Facilitação de Dojos

> “É normal perder para o adversário. Nunca é bom perder para o medo.”
> 
> ― Sr. Miyagi, *Karate Kid*

## O que é um Coding Dojo?

Nas artes marciais, um dojo tradicional é um ambiente de aprendizado e treinamento, e o mesmo pode ser dito sobre o Coding Dojo: é um evento (ou uma série de eventos) de [mob programming](https://www.agilealliance.org/resources/experience-reports/mob-programming-agile2014) em que pessoas se encontram e com algumas poucas regras buscam aprender programação colaborativamente e se divertir.

A nossa filosofia de Coding Dojo é baseada em três pilares principais:

1. Aprendizado contínuo: venha para aprender e ensinar, sem se distrair com outras coisas.
2. Ambiente seguro: não saber, errar e fazer perguntas é perfeitamente normal, e nada disso será usado contra você.
3. Baby steps: é preciso saber andar antes que se possa correr, e por este motivo a resolução do desafio acontecerá em pequenos incrementos.

## Requisitos

Para rodar um Coding Dojo você precisará:

1. Alguém para facilitar: uma pessoa com alguma experiência anterior em Coding Dojos
2. Um desafio: algum desafio de programação que será resolvido pelos participantes
3. Um ambiente preparado: um computador com as ferramentas necessárias instaladas e prontas para iniciarmos a resolução do desafio

### 1. Alguém para facilitar

A pessoa que vai facilitar deve ser alguém que já tenha participado de algum Coding Dojo e se divertido. O conhecimento técnico desta pessoa sobre a linguagem que será utilizada ou qualquer tipo de tecnologia deve ser suficiente para escolher o desafio que será resolvido e preparar o ambiente em que o Dojo será rodado.

### 2. A escolha do desafio

O desafio escolhido para o Coding Dojo deve levar em conta:

a. O objetivo de aprendizado dos participantes: Se queremos aprender mais sobre recursos básicos de uma linguagem ou simplesmente experimentar o funcionamento de um Dojo, um desafio com menos raciocínio lógico provavelmente seria o ideal. Agora, se queremos aprender mais sobre algoritmos, um desafio lógico faria muito mais sentido.

b. O nível técnico dos participantes: Se a maior parte dos participantes já domina a tecnologia utilizada, um desafio mais complexo talvez seja o apropriado. Se teremos na sala pessoas sem conhecimento prévio da tecnologia utilizada, um desafio mais básico seria mais apropriado.

c. Diversão: Se os participantes, de forma geral, não gostam de algum tipo de tecnologia ou problema, talvez escolher um desafio mais alinhado às vontades dos participantes faça mais sentido. A não ser que o objetivo de aprendizado do Dojo seja quebrar esses preconceitos.

Escolher um desafio que você já tenha resolvido antes como base para criar um novo, ou manter um desafio já resolvido só alterando a tecnologia utilizada são boas opções na escolha do desafio.

### 3. O ambiente

Nunca deixe para fazer o setup do ambiente em que o Dojo será rodado no mesmo dia do Dojo. A chance de dar ruim é grande, e começar um Dojo tendo que resolver problemas de ambiente geralmente é bem chato.

Conversar ou até [parear](https://martinfowler.com/articles/on-pair-programming.html) com pessoas que já tenham conhecimento sobre a tecnologia que será utilizada no Dojo ajuda muito na preparação do ambiente. Inclusive, dar uns pequenos passos na resolução do desafio já durante o setup é uma boa forma de garantir que começaremos o Dojo mais suave. 

#### Ferramentas

Se o Dojo for rodado presencialmente, as ferramentas essenciais são: Um projetor ou televisão grande o suficiente para todos lerem o que está escrito, um computador com o ambiente preparado, uma mesa e cadeira com mouse e teclados a uma distância boa o suficiente da televisão e assentos confortáveis para a platéia (preferencialmente em U).

Agora, se o Dojo for rodado remotamente, existem algumas opções de ferramentas que podem ser utilizadas:

1. [Zoom](https://zoom.us): O Zoom tem uma feature chamada ["remote control"](https://support.zoom.us/hc/en-us/articles/201362673-Requesting-or-giving-remote-control). Ela funciona muito bem. Caso você opte por rodar o Dojo utilizando somente o Zoom, tudo o que você vai precisar preparar é o ambiente no seu computador e dar acesso remoto a ele pelo próprio Zoom para quem for pilotar no momento em que for pilotar.

2. [VSCode Live Share](https://code.visualstudio.com/learn/collaboration/live-share): Essa extensão do Visual Studio Code permite que várias pessoas colaborem no mesmo código em tempo real. É quase mágica! Se você optar por utilizá-la no Dojo, lembre-se que cada participante já deve ter em seu computador o [VSCode](https://code.visualstudio.com/) instalado com [a extensão](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack) funcionando. Não necessariamente cada participante precisará ter o ambiente já configurado na sua própria máquina, já que o VSCode Live Share permite o uso do console do host (quem está facilitando, geralmente).

3. [Replit](https://replit.com/): Uma IDE gratuita, colaborativa, que roda no browser e suporta mais de 50 linguagens de programação. Não exige nenhum setup, mas exige cadastro.

4. [Mob.sh](https://mob.sh/): Outra alternativa ousada. Experimenta aí!

## Rodando o dojo

Com tudo preparado e os participantes presentes, é hora de começar! Quem facilita explica brevemente o que é um dojo e como ele funciona. Os participantes são divididos em três papéis, sendo que cada participante pode mudar de papel a cada poucos minutos.

### Os papéis

1. Quem pilota: é quem escreve o código. É importante que quem assume esse papel detalhe o que está fazendo, quais são suas ideias, e também que converse continuamente com quem navega. Dessa forma garantimos que todos os participantes entendam o que está acontecendo e aprendam.
2. Quem navega: é aquele que guia e conversa com quem está pilotando, apontando problemas, contribuindo com sugestões e pesquisa quando necessário. Quem navega também é livre para explicar o que está acontecendo e quais são suas ideias, assim como o piloto.
3. Plateia: são os demais participantes, que observam e se mantém em silêncio, embora possam contribuir caso quem pilota ou quem navega peça ajuda.

### As rodadas

- A dupla de quem pilota e quem navega age em conjunto durante uma rodada, que geralmente tem uma duração entre dois e cinco minutos. Normalmente cabe a quem facilita definir qual é a duração da rodada, sendo que rodadas curtas de dois minutos funcionam bem para desafios simples e/ou para participantes experientes no assunto do desafio, enquanto rodadas mais longas de até cinco minutos são melhores para desafios complexos e/ou participantes experientes no assunto do desafio.
- Aquele que facilita, ou um voluntário da plateia, se encarrega de cuidar do timer. Assim que o tempo do timer começa a correr, é importante que a plateia permita que apenas quem pilota e quem navega falem, a não ser que estas duas pessoas peçam ajuda.
- Ao fim de uma rodada os papéis são trocados. Quem navegou retorna para a plateia. Quem pilotou se torna quem navega na rodada seguinte, e alguém da plateia se voluntaria para pilotar na rodada seguinte. É costume que se dê preferência dos papéis principais a quem ainda não os ocupou.
- No intervalo entre rodadas é comum que aquele que facilita comente sobre o desenvolvimento do desafio e quais seriam os próximos passos. Todos os participantes, independente de seu papel atual, também são livres para fazer comentários, perguntas ou explicações mais detalhadas sobre o que aconteceu e sobre os passos seguintes.

### Começando o desafio

Uma vez que esteja claro o funcionamento do dojo, quem facilita apresenta o desafio. Também é comum que esta pessoa dê uma explicação sobre os conceitos e problemas envolvidos, e até mesmo que escreva as primeiras uma ou duas linhas de código para colocar os demais participantes no rumo esperado. Os participantes se voluntariam para pilotar e navegar, e é definido quem cuidará do timer. Feito isso o dojo está prestes a começar! Basta seguir o modelo de papéis e rodadas descritos acima até que o desafio seja concluído.

## Dicas de ouro

- Compartilhar a tela o tempo todo é essencial!
- Use e abuse de timebox. O timer do [slice.tools](https://slice.tools) é uma boa ideia, já que é compartilhado por todos que acessam a mesma URL.
- No começo do dojo, como facilitador, fale das suas inseguranças e desconhecimentos também, não só da parte que você curte/está confortável. Demonstrar vulnerabilidade (real) quando está conduzindo o encontro gera mais empatia e faz os outros se sentirem a vontade para errar.
