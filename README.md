# Estudos
Desenha o código

---
## Java
---
## Git
---
## DevOps (Development Operation)
É um conceito, são práticas de trabalho e várias ferramentas que ajudam nesse trabalho

---
## Containers
É uma ferramenta, funciona como uma espécie de virtualização modular, pois é possível virtualizar apenas uma parte da aplicação, não ela toda.\
Docker é uma aplicação que gerencia containers, mas não é a única.

---
## Kubernets
Aplicação para orquestrar containers.\
Não é a única que tem, mas é a mais utilizada.

---
## Pipeline
Pipeline é uma sequência de etapas para colocar uma aplicação em produção.

---
## Clean Code


Analista de negócio?

BDD

O que fiz até agora:
- no site do cucumber tem um cursinhos de uso da ferramenta. Estou fazendo eles, enquanto vou procurando mais informações em vários lugares. Achei coisas boas no YouTube de um colega teu Engenheiro de software, Rafael Lima.
- To tendo alguma dificuldade com o Inglês, mas nada que me trave, meu inglês é bom o suficiente para jogar video game, mas não tão bom para ler uma documentação, só questão de treino.
- Ainda não fiz um ambiente de desenvolvimento, não instalei nem uma ferramenta ou algo assim, primeiro quero solidificar os conceitos básico, para então começar a tentar desenvolver algo. Acho que isso vai acontecer naturalmente amanhã.

Minhas questões:
Não são exatamente questões técnicas, são mais questões para eu ir encontrando meu espaço
- Em quanto tempo tu espera algum retorno, uma implmentação de teste, algo nesse sentido. 3 dias, uma semana, duas semanas? Serve mais como parâmetro pra eu me preparar mesmo, e conseguir atender as expectativas postas.
- Gosto sempre de ter feedback, principalmente críticos, então fico aberto quanto a isso.

No mais estou gostando bastante da aplicação do BDD, ainda é pouco conhecimento da pra ver muito potencial
---
Gosto de ter feedbacks críticos, são feedbacks que me ajudam a melhorar.
Quanto tempo tu espera ter algum retorno?

https://cucumber.io/blog/collaboration/the-worlds-most-misunderstood-collaboration-tool/

---
---

Conceitos para pesquisa:
- living documentation


1 .
O que significa BDD?

BDD é uma abordagem que especifica de forma colaborativa o comportamento desejado do sistema. Cada vez que um comportamento é acordado, usamos essa especificação para "dirigir" o desenvolvimento do código que implementará esse comportamento.
---

2 .
Quais são as três práticas do BDD e em que ordem você as aplica a uma história?

Começamos descobrindo colaborativamente o escopo do comportamento exigido pela história. Depois de concordarmos com esse comportamento, formulamos a especificação em linguagem legível para os negócios. Por fim, automatizamos  a especificação formulada para verificar se o sistema realmente se comporta conforme o esperado.
---

3 .
Como o Cucumber e o BDD estão relacionados?

O Cucumber é uma ferramenta que entende sua documentação e a transforma em testes automatizados.
O BDD é uma abordagem colaborativa, composta por três práticas. Os praticantes de BDD podem usar o Cucumber para automatizar sua documentação.
---

4 .
O que há de especial na “documentação viva”?

Chamamos isso de "Documentação Viva" porque a documentação nos informa automaticamente quando sai de sincronia com o comportamento do aplicativo. É isso que tem de especial.

Você pode revisá-lo como parte de sua definição de concluído, mas isso também vale para qualquer tipo de documento de especificação que você escreveu, mesmo que não tenha sido validado automaticamente.

Não é gerado por testes automatizados - você ainda precisa escrevê-lo! Os testes automatizados apenas informam se o que você escreveu é verdade ou não. 

Você pode muito bem ter um processo de controle de alterações para ele - nós o encorajamos a mantê-lo no controle de origem com o código que ele descreve - mas, novamente, isso não é nada de especial. Você pode ter um processo de controle de alterações maravilhosamente transparente para um documento do Word e ainda pode estar completamente desatualizado e errado.
---

1 .
Praticantes de BDD preferem documentação abrangente em vez de colaboração

BDD é uma atividade colaborativa. A documentação viva é uma saída secundária e valiosa da aplicação das práticas de BDD.
---
2 .
Qual é a relação entre BDD e ágil?

O BDD é uma coleção de práticas que se baseiam em formas ágeis de trabalho, ajudando as equipes a terem sucesso. Para que essas práticas agreguem valor, você precisará trabalhar de maneira ágil.
---
3 .
O que há nas Histórias de Usuário que ajuda uma equipe a fazer BDD?

As histórias de usuários foram criadas para serem "espaços reservados para uma conversa". Eles nos permitem adiar uma análise detalhada até que tenhamos certeza de que o comportamento que descrevem realmente precisa ser desenvolvido.
---

1 .
Por que o chamamos de “Três Amigos”?

O objetivo de uma reunião de três amigos é garantir que a equipe entenda completamente o escopo da história que está sendo discutida. Para que isso seja eficaz, precisamos ter pelo menos três perspectivas diferentes representadas na reunião.
Mais de três pessoas podem participar de uma reunião de três amigos, porque:
algumas histórias são amplas o suficiente para exigir a entrada de mais de três perspectivas
mais de um representante de cada perspectiva pode participar
---

2 .
Quem são os três amigos?

As três perspectivas essenciais necessárias são:

perspectiva do cliente/negócio - geralmente fornecida pelo Product Owner
perspectiva de desenvolvimento - geralmente fornecida por um desenvolvedor
perspectiva de teste - geralmente fornecida por um testador
---

3 .
O grupo descobriu uma nova regra de negócios durante a reunião. Por quê?

Todo o propósito do encontro dos três amigos é descobrir coisas sobre a história que não eram óbvias anteriormente. Devemos esperar aprender coisas novas durante uma reunião de três amigos.
---

1 .
Por que as perguntas são uma saída valiosa de uma sessão de descoberta?

Queremos descobrir nossas áreas de ignorância antes de começarmos a desenvolver a próxima funcionalidade. Se ainda tivermos perguntas não respondidas sobre uma funcionalidade, é improvável que estejamos em condições de começar a trabalhar nela.
Antes do workshop de descoberta, a pergunta não havia sido feita. Isso significa que era um problema desconhecido  - era algo que desconhecíamos completamente. Agora que fizemos a pergunta, é uma incógnita conhecida - estamos cientes de que é uma área sobre a qual precisamos aprender mais.
Tendo descoberto a questão, a equipe agora tem uma área concreta para investigar, aprendendo mais sobre o problema que está sendo solicitado a resolver.
---

2 .
Por que as habilidades de teste são valiosas durante a descoberta?

A perspectiva de teste é essencial durante o processo de descoberta. Isso nos permite fazer perguntas difíceis de estilo " e se " que garantem que pensamos sobre a história em detalhes. A equipe usa exemplos concretos para testar sua compreensão do que está sendo solicitado, enquanto também testa a compreensão do proprietário do produto sobre a funcionalidade que está solicitando.
---

1 .
O que é Gherkin?

Gherkin é uma sintaxe simples que permite que as equipes escrevam especificações executáveis ​​e legíveis para os negócios. 
Algumas das palavras-chave Gherkin são Given, When  e Then , mas nem todo texto que usa essas palavras é Gherkin.
O Gherkin é compreendido por um grande número de ferramentas, notadamente Cucumber e Specflow, que efetivamente transformam a especificação em testes automatizados.
---

2 .
Qual é a relação entre um cenário e um exemplo?

**Durante três amigos, a equipe usa exemplos concretos para garantir que eles tenham um entendimento compartilhado da funcionalidade que estão prestes a desenvolver. Esses exemplos concretos são formulados  em cenários Gherkin.**
Assim, cada cenário é um exemplo.
Cenário e Exemplo são palavras-chave no Gherkin.
---

1.
Qual é a vantagem de usar Gherkin para expressar os nossos exemplos em BDD?

Gherkin é apenas uma forma de expressar exemplos de como desejamos que o sistema se comporte. A vantagem de utilizar este formato específico é que pode usar o Cucumber para os testar para si, transformando-os em Documentação Viva.
---

2.
Quais destas são as palavras-chave de Gherkin?

Introduzimos quatro palavras-chave Gherkin até agora: 

Cenário(Scenario) diz ao Pepino que estamos prestes a descrever um exemplo que ele pode executar.\
Dado(Given), Quando(When) e Depois(Then) para identificar as etapas do cenário.\
Há algumas outras palavras-chave que serão introduzidas mais tarde no decurso do curso.
---

3.
As palavras-chave Gherkin Given, When e Then, permitem-nos expressar três componentes diferentes de um cenário.

Qual destas afirmações descreve correctamente como cada uma destas palavras-chave deve ser utilizada?

Dado(Given) é o contexto para o cenário. Estamos a colocar o sistema num estado específico, pronto para que o cenário se desdobre.

Quando(When) é que é uma acção. Algo que acontece ao sistema e que fará com que algo mais aconteça: um resultado.

Então(Then) é o resultado. É o comportamento que esperamos do sistema quando esta acção acontece neste contexto.
---

4.
Porque é que o nosso cenário não mencionou nada sobre a Lucy entrar na loja do Sean e fazer uma compra?

Os profissionais do Desenvolvimento Orientado pelo Comportamento preocupam-se definitivamente com os objectivos comerciais, mas quando estamos a escrever a parte do Cenário do nosso Gherkin, precisamos de nos concentrar no comportamento observável e verificável do sistema que estamos a construir.
Mais tarde, no curso, mostraremos como se pode utilizar outras partes dos documentos Gherkin para acrescentar outros detalhes relevantes, como objectivos empresariais, para fazer grandes especificações executáveis.
---

---
acredito que a implementação BDD pode ocupar um espaço de
Qualidade e documentação, pode preencher essa lacuna 

Tranquilo então.
Amanhã de manhã te trago boas novidades.
Caso surja algo que eu julgue importante durante o dia de hoje, eu te mando mensagem.


Let's imagine we're building a point-of-sale system for an electronics retailer

Ao longo deste curso, trabalharemos em um aplicativo real, acompanhando seu desenvolvimento desde o início, usando BDD e Cucumber para nos guiar ao longo do caminho.

Neste capítulo vamos:
- Saiba mais sobre o Shouty, nosso projeto de exemplo
- Escreva nosso primeiro cenário em Gherkin
- Instalar pepino
- Use o Cucumber para nos guiar na implementação de uma solução muito ingênua

	Shouty é uma rede social que permite que pessoas fisicamente próximas se comuniquem, assim como as pessoas sempre se comunicaram com suas vozes. No mundo real, você pode conversar com alguém na mesma sala ou do outro lado da rua. Ou mesmo 100 m de distância de você em um parque - se você gritar.

	Isso é Shouty. O que você diz nesta rede social só pode ser “ouvido” por pessoas que estão por perto.

	Vamos começar com um exemplo muito básico do comportamento de Shouty. Algo que poderíamos ter discutido em uma reunião de três amigos:

	> Sean, o gritador, grita "bagels grátis no Sean's" e Lucy, a ouvinte que está do outro lado da rua de sua loja, a 15 metros de distância, o ouve. Ela entra no Sean's Coffee e aproveita a oferta.

Podemos traduzir isso em um cenário Gherkin para que o Cucumber possa executá-lo. Veja como isso ficaria.

		Scenario: Listener is withing range
			Given Lucy os located  15m from Sean
			When Sean shouts "free bagels at Sean's"
			Then Lucy hears Sean's message

Você pode ver que há quatro palavras-chave especiais sendo usadas aqui. **Scenario** apenas diz ao Cucumber que estamos prestes a descrever um exemplo que ele pode executar. Então você vê as linhas começando com **Given**(Dado), **When**(Quando) e **Then**(Então).

- Given é o contexto para o cenário. Estamos colocando o sistema em um estado específico, pronto para o cenário se desenrolar.

- When é uma ação. Algo que acontece com o sistema que fará com que outra coisa aconteça: um resultado.

- Then é o resultado. É o comportamento que esperamos do sistema quando essa ação acontece nesse contexto.

Você notará que omitimos de nosso resultado qualquer coisa sobre Lucy entrando na loja e fazendo uma compra. Lembre-se, Gherkin deve descrever o comportamento do sistema, então seria uma distração tê-lo em nosso cenário.

Cada cenário tem esses três ingredientes: um contexto, uma ação e um ou mais resultados.

Juntos, eles descrevem um único aspecto do comportamento do sistema. Um exemplo.

Agora que traduzimos nosso exemplo para o Gherkin, podemos automatizá-lo!

---

A maneira mais fácil de começar com o Cucumber for Java é usar um projeto de modelo com um script de construção que configura tudo corretamente.

Você pode baixar este projeto de modelo do GitHub. Abra seu navegador e vá para o projeto “Cucumber Java Skeleton” no GitHub.

Se você estiver confortável com o Git, você pode simplesmente clonar o projeto.

O projeto de modelo contém scripts de construção Maven e Ant que facilitam a introdução ao Cucumber para Java.

Nós estaremos usando o Maven, então se você ainda não o instalou, agora é um bom momento para fazer isso.

Vamos dar uma olhada no que mais está neste projeto.

Há um diretório principal para nosso código de aplicativo e um diretório de teste para nosso código de teste. Vamos remover alguns dos arquivos que acompanham o projeto.

Remova Belly.java, StepDefinitions.javae belly.feature.

Agora temos um projeto básico. Vamos construí-lo desde o início para que você possa ver o que está acontecendo.

Antes de abrirmos o projeto em nosso IDE, vamos modificar o nome do aplicativo.

Abra pom.xml e altere o ID do grupo, o ID do artefato e o nome.

Estamos prontos para começar a codificar! Vamos usar o IntelliJ IDEA Community Edition porque ele tem uma integração muito boa com o Cucumber embutida. Se você preferir usar um IDE diferente, como o Eclipse, tudo bem também.

Para abrir o projeto no InteliJ, basta abrir o arquivo pom.xml.

Antes de criarmos qualquer arquivo, vamos renomear o pacote de esqueleto para shouty. No InteliJ você pode renomeá-lo através do menu Refactor.

Agora estamos prontos para criar nosso primeiro arquivo de recurso.

1 .
O que significa quando o Cucumber diz que uma etapa é indefinida?

Cada linha em um Cenário que começa com uma das palavras-chave Dado/Quando/Então é chamada de etapa .
Quando o Cucumber nos diz que uma etapa é indefinida, isso significa que ele não sabe o que queremos fazer para automatizar essa etapa. Temos que dizer ao Cucumber o que fazer fornecendo definições de etapas .
Aprenderemos sobre as definições de etapas na próxima lição.

---
---
Possível curso para fazer
https://smartbear.com/resources/webinars/get-users-stories-into-shape-with-example-mapping/?utm_medium=cucumper-doc&utm_source=referral&utm_campaign=shape-example-mapping

Para definir:
- Apache Maven 
- Grandle

Para entender
# Primeiro é necessário saber o que é BDD e como funciona

> BDD - Desenvolvimento Orientado a Comportamento

> É uma maneira de trabalho que envolve no mesmo círculo pessoas do negósio\
> e pessoas técnicas



# Depois a gente entra do Gherkin e no Cucumber

Primeiro:
Criar um cenário(link para utils\cenarios)
De onde sugem os cenários?
Cenários são exemplos concretos, um passo a passso da implementação menor possível. Algo que existe


# utils

## cenários
Descrever um cenários aqui
O que é?
cenários são expecificados em arquivos .feature
Como montar o código?
