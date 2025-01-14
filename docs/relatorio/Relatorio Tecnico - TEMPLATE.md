# Informações do Projeto
`Idiomatize`  

`Ciência da Computação`

## Participantes

> Os membros do grupo são: 
> - Gabriel Bruno Borges
> - Isabela França Prates 
> - Tulio Resende Melgaço 

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

No nosso projeto focamos em estudar a fundo o problema de estudar uma nova língua, quem sente essa dor, o porquê dessa dor, como é possivel amenizar essa dor e o que as pessoas gostariam de ter como ferramenta para auxilia-las. Assim, estamos desevolvendo uma solução, carinhosamente chamada de "Idiomatize", para que quem enfrenta essa questão de sofrer para aprender uma língua seja amparado.

## Problema

A cada dia que passa o mundo se torna mais e mais globalizado, tendo isso em vista muitas pessoas se veem em um cenário no qual saber uma única língua é insuficiente, seja por oportunidades no mercado de trabalho, sonho de morar fora, comunicar com pessoas de outros países, consumir conteúdo em outra língua, viajar, entre outras várias coisas. Ademais, quem que não falam inglês e desejam aprender uma língua (ex Mandarim) não encontram nenhum material traduzido para estudar, tornando quase impossível esse processo de aprendizagem. Sem falar que, dependendo da língua, mesmo sendo fluente em inglês é extremamente difícil encontrar bons materiais. Por fim, muitas dessas pessoas não tem como pagar financeiramente para ter acesso a um ensino bom ou recursos de qualidade.

## Objetivos

O objetivo do nosso grupo é desenvolver um software que facilite o aprendizado de linguas para quem tem interesse ou necessita aprender um novo idioma. Temos como foco a criação de algo que possa ser acessível a todos, e que os usários tenham como exercitar o aprendizado em qualquer lugar e a qualquer momento de forma simples, prática, mas ao mesmo tempo eficiente. Vale enfatizar que pretendemos dar luz a um projeto dinâmico, tendo em vista que durante entrevistas com possíveis futuros usúarios averiguamos que o maior empecilho para o aprendizado de um novo idioma é a falta de tempo, que se faz cada vez mais frequente no atual mundo globalizado.

## Justificativa

Nós escolhemos este tema justamente por que achamos que é algo muito importante tanto na formação acadêmica de qualquer pessoa quanto na vida dela, é um assunto muito importante e queremos ajudar como resolvê-lo.
O objetivo do nosso grupo é desenvolver um software que facilite o aprendizado de linguas para quem tem interesse ou necessita aprender um novo idioma. Temos como foco a criação de algo que possa ser acessível a todos, e que os usários tenham como exercitar o aprendizado em qualquer lugar e a qualquer momento de forma simples, prática, mas ao mesmo tempo eficiente.
A cada dia que se passa a nessecidade de aprender novas linguas aumenta mais, sendo por qualquer motivo, a vontade de aprender ou por que precisa aprender, e ja que o nosso problema é "Aprender Linguas" logo identificamos nosso publico alvo, que seriam pessoas que querem ou precisam aprender línguas, pessoas que estão insatisfeitas com as ferramentas que usam para aprender línguas, alunos que praticam o estudo de outras linguas, os professores que irão aprender para depois ensinar para outras pessoas, pessoas que irão mudar de país e precisam conhecer uma nova lingua, seja ela qual for e é claro as Instituições de ensino.
Nossa fonte e onde nosso trabalho foi baseado são em entrevistas com nosso público alvo e conversas, pois eles são a melhor fonte que podemos ter sobre nosso problema!

## Público-Alvo
Nosso publico alvo são pessoas de qualquer idade, que sabem acessar sites e que querem, precisam ou já estão aprendendo outras línguas. Assim pessoas que estão insatisfeitas com as ferramentas que usam para aprender línguas, alunos que praticam o estudo de outras linguas, pessoas que buscam novas oporunidades no emprego ou na faculdade e pessoas que irão mudar de país são nosso foco para esse trabalho.

![image](https://user-images.githubusercontent.com/90773483/191873944-93004095-72b7-415f-81fd-e6478c858800.png)


# Especificações do Projeto

## Personas e Mapas de Empatia

![image](https://user-images.githubusercontent.com/113730402/191875415-fc8945ae-ba4e-4c64-9ae2-418a96b155d0.png)
![image](https://user-images.githubusercontent.com/113730402/191875443-c0df3e38-29df-49bd-a67e-dc21a45a9260.png)
![image](https://user-images.githubusercontent.com/113730402/191875457-4199a330-40eb-40b4-bda8-a62038820094.png)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Treinar minha escuta na língua     | Ser capaz de ter uma comunicação plena |
|Usuário do sistema  | Interagir com outras pessoas       | Engajar no estudo e compartilhar coisas|
|Usuário do sistema  | Ver minha frequencia no site       | Me organzar melhor e ter disciplina    |
|Usuário do sistema  | Fazer questões para me testar      | Ver se estou aprendendo                |
|Usuário do sistema  | Aprender sobre as culturas         | Facilitar a troca internacional        |


>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre textos de estudo | ALTA | 
|RF-002| Armazenar as informações de frequencia do usuário   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-003|	O cadastramento de informações deve ser rapido e fácil|	ALTA

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03|	O projeto deve respeitar as datas de entrega         |
|04|	Não devera ter ajuda de terceiros no projeto         |


# Projeto de Interface

## User Flow

![image](https://user-images.githubusercontent.com/113730402/191881404-88604584-e225-4a8b-8ac0-04e09d7ddd74.png)

## Wireframes

![16](https://user-images.githubusercontent.com/98985632/192395747-3931fd46-7bb6-4e5d-9755-956f05e9ada5.png)
![17](https://user-images.githubusercontent.com/98985632/192395750-f43eeb28-18fb-49aa-979a-9dd70b8991c5.png)
![18](https://user-images.githubusercontent.com/98985632/192395754-6fe38600-7a61-43fa-bf51-791cf7a9e67a.png)
![19](https://user-images.githubusercontent.com/98985632/192395758-76de016d-2c71-40c5-ac31-8f357b4c63b2.png)
![20](https://user-images.githubusercontent.com/98985632/192395760-14357a03-c061-4694-a556-cd2d802209ee.png)
![155](https://user-images.githubusercontent.com/98985632/192395761-619e495f-efb3-4288-97fb-97945a1ea393.png)
![166](https://user-images.githubusercontent.com/98985632/192395765-204f3b33-6007-4aa5-bbc0-94ed0ae2d5b5.png)
![177](https://user-images.githubusercontent.com/98985632/192395770-52284646-d7b0-47fc-94ee-8225d2d6ac88.png)
![13](https://user-images.githubusercontent.com/98985632/192395772-374448ef-58dd-4c16-bf5e-f8a522179a23.png)
![14](https://user-images.githubusercontent.com/98985632/192395775-9ba2333f-4f4e-4371-9290-86d2af2c997b.png)
![15](https://user-images.githubusercontent.com/98985632/192395743-ea85b192-1718-4c1d-8bbe-5b249cf9d52f.png)



# Metodologia


O grupo resolveu dividir as tarefas de forma que nenhum membro do grupo fique sobrecarregados. Estipulamos datas de entrega e analisamos em grupo as entregas. Assim, para fazer isso usamos a metodologia Scrum, e nos reunimos ao longo da semana para ver o progresso de cada um. Demos preferencia para ferramentas que todos podiam acessar juntos, como o Miro, o Canva e o GitHub.


## Divisão de Papéis

- Github -- Gabriel e Túlio
- Wireframe -- Isabela
- Miro -- Todos


## Ferramentas

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/welcomeonboard/MzFTTEU2SGF2MWxoTnNLNWxESkZEVkc4Y0tKbWozT2lLcVh1dlk5aHI5ODQ1cTBGT29LMWd4VG9jeldncnF6NnwzNDU4NzY0NTMzMjc3NDAyODUwfDI=?share_link_id=136255874979 | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com |  

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
