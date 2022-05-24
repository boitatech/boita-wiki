# Security Champions - Tradução v1
[Security Champions Playbook](https://github.com/c0rdis/security-champions-playbook)

[Security Champions: Você precisa pensar sobre isso](https://blog.convisoappsec.com/security-champions-voce-precisa-pensar-sobre-isso/)

[Programa Security Champions: o que é e como fazemos na Zup](https://www.zup.com.br/blog/programa-security-champions)

## 1. Identificação dos times

O principal objetivo desta etapa é mapear os problemas das equipes com as quais você trabalhará, é extremamente importante anotar e mantê-la em local público conhecido e acessível a todos. Conversas individuais com proprietários de produtos e líderes de engenharia seriam um bom começo para essa etapa do processo.

Perguntas típicas que devem serem feitas para te ajudar nesse processo:
- Quantas equipes estão trabalhando por produto
- Quais tecnologias (linguagens de programação, frameworks) os times estão usando
- Onde está armazenado o código e a documentação das aplicações
- Quais ferramentas automatizadas e serviços externos/internos são usados para desenvolvimento e realização dos testes
- Qual é o processo de revisão de código (incluindo revisão de código de segurança) que cada equipe está usando e quem está envolvido
- Existem outras atividades relacionadas à segurança com foco no produto, além de revisões de código
- Qual é o calendário de lançamento/ciclo/estágio atual do produto
- Quais são os canais de comunicação mais utilizados pelo produto
- Como se costuma relatar um problema/bug de segurança do produto e quem está cuidando disso

O resultado deste exercício deve ser uma página no wiki interno com uma tabela como o seguinte modelo:

| Produto  | Team  |  Tecnologias  | Security contact | Team lead  | Product manager |
| -------- | ----- | ------------- | ---------------- | ---------- | --------------- |
|   Name   | Alpha |     Python    |    John Smith    | Anna Nowak |    Anna Nowak   |

## 2. Definindo o papel

O principal objetivo desta etapa é apresentar descrições claras das funções dos Security Champions. Com o seu programa AppSec e metas globais definidas, é crucial distinguir as atividades que mais correspondem aos Security Champions e mapeá-las para essas metas.

Dependendo do estado atual da segurança em sua organização, isso pode incluir alguns ou todos os itens abaixo:

- Conduzir e/ou verificar revisões de segurança na equipe
- Proteger e promover as melhores práticas
- Levantar questões para riscos no código existente e nos novos
- Realizar modelagem de ameaças para os novos recursos
- Conduzir e/ou verificar varreduras automatizadas
- Investigar relatórios de recompensas de bugs
- Participar de atividades de P&D (pesquisa e desenvolvimento)

## 3. Nomeando Security Champions

Você deve primeiro obter aprovação da gerência em todos os níveis. Faça uma apresentação das funções definidas, benefícios para a equipe e tempo aproximado que o Security Champions gastaria nas tarefas de segurança, -20% deve ser suficiente para o início.

Após ter essas aprovações, o próximo passo seria identificar potenciais Security Champions. Sente-se junto com o gerente da equipe, selecione os candidatos e realize mini-entrevistas com cada um deles. Lembre-se - *it's not appointing but nominating!*.

Descreva o papel, as expectativas e a estratégia e mostre a eles os benefícios pessoais de se tornar um Security Champions:

- Autodesenvolvimento e capacidade de ver as coisas de maneira diferente
- Aumento do seu valor de mercado
- Melhorando a qualidade do produto
- Participando de conferências de segurança
- Tornando-se uma parte importante da meta-equipe de segurança
- Se divertindo :)

A parte final dessa etapa é a nomeação oficial e a apresentação do mesmo aos outros.

## 3.1 Processo de onboarding

Os Security Champions vêm e vão e é importante estabelecer uma rotina de integração. As etapas comuns são:

- Apresentar os novatos aos outros Security Champions
- Comunicar os novos participantes para toda a empresa
- Adicione-os a todos os canais de comunicação
- Introduzir a base de conhecimentos e incluí-los nos ciclos de formação
- Atribuir a primeira tarefa
- Tenha 1:1s periódicos

## 4. Configurando canais de comunicação

Os Security Champions indicados *não podem operar sozinhos*, funciona melhor quando eles realmente sentem o espírito de equipe. Dependendo da cultura corporativa, pode ser os seguintes:

- Canais privados do Slack/IRC
- Equipes de base de chave
- Bate-papos em grupo do Skype
- Grupos do Yammer
- Listas de discussão
- Formulários Google

Apenas certifique-se de que há uma maneira fácil de divulgar informações importantes e obter feedback. Além disso, configure sincronizações periódicas para ver como as coisas estão indo e para ajustar as metas de curto prazo. Para o início, reuniões quinzenais devem funcionar bem. 

> Certifique-se de que as comunicações do ambiente não sejam tóxicas e que todos os Security Champions se sintam seguros para expressar suas dúvidas, preocupações e propostas.

## 5. Construindo uma base de conhecimento sólida

O principal objetivo desta etapa é a base de conhecimento interna ser a principal fonte de respostas para perguntas relacionadas à segurança. Além da página da meta-equipe, que permite que qualquer pessoa encontre rapidamente o contato certo, as páginas a seguir serão bastante úteis:

- Estratégia de segurança global
- Funções e procedimentos de segurança claramente definidos
- Práticas recomendadas de desenvolvimento seguro
- Algoritmos de criptografia recomendados
- Descrição de riscos e vulnerabilidades comuns
- Políticas de senha

Projetos OWASP, como [Security Knowledge Framework](https://www.securityknowledgeframework.org/), [ASVS](https://owasp.org/www-project-application-security-verification-standard/) e [MASVS](https://github.com/OWASP/owasp-masvs), bem como as melhores práticas do setor (por exemplo, padrões de codificação segura [CERT](https://www.securecoding.cert.org/confluence/display/seccode/SEI+CERT+Coding+Standards)) serão um excelente ponto de partida para criar a base dos primeiros workshops internos.

## 5.1 Treinamento e qualificação

Uma abordagem positiva é fornecer treinamento básico de nivelamento dos Security Champions que teve pouca ou nenhuma exposição à segurança. Fornecendo a orientação e os recursos necessários, podemos garantir que os Security Champions estejam prontos para cenários mais complexos.

Os tópicos a serem discutidos devem ser bem escolhidos de acordo com a definição do papel. Alguns tópicos que geralmente são úteis:

- Security Champions Program 101
- Boas práticas de desenvolvimento seguro
- Classificação de vulnerabilidades
- Offensive Security Assessments
- Modelagem de Ameaças
- Resposta a incidentes
- Políticas e procedimentos internos

As sessões de treinamento devem ser curtas e fornecer indicadores para uma lista com curadoria de recursos detalhados, bem como ilustrar cada tópico com exemplos reais da organização.

> Juntamente com o treinamento, recomenda-se esclarecer e documentar os processos internos nos quais é esperado que o Security Champions desempenhe os papéis de gerenciamento de vulnerabilidades, tratamento de incidentes, ferramentas recomendadas (ou seja, SAST, DAST, SCA, plugins de segurança, etc.).

Assuntos que são específicos apenas para um determinado conjunto de Security Champions podem ser abordados após os principais tópicos terem sido abordados.

Os campeões devem ser incentivados a pesquisar e apresentar proativamente tópicos relacionados às suas principais áreas de especialização.

Exemplo de tópicos específicos da plataforma:

- Android/iOS security (mobile)
- Spring Boot Security (back-end)
- XSS vulnerabilities in Angular/React/Vue (front-end)
- Writing secure IAM policies (infra/cloud)

## 5.2 Formatos de treinamento

Um bom programa de treinamento pode incluir os seguintes componentes:

- Materiais de referência da base de conhecimento
- Sessões ao vivo
- Hands-on practice
- Avaliações de desempenho

As *sessões ao vivo* são úteis para agendar um horário periódico para o Security Champions conhecer e compartilhar experiências, promovendo um senso de comunidade e melhorando o nível de engajamento.

*Hands-on practice* deve consistir em laboratórios desenvolvidos internamente ou externamente, onde os participantes possam trabalhar sozinhos em cenários semelhantes aos que devem enfrentar.

As *avaliações de desempenho* são os instrumentos pelos quais o sucesso do programa de treinamento pode ser medido. Ao estabelecer critérios mínimos de sucesso em cada tema abordado, pode-se considerar que os Security Champions receberam insumos suficientes para desenvolver suas atividades de acordo.

## 5.3 Níveis dos Security Champions

Para garantir que o Security Champions tenha exposição suficiente aos tópicos com os quais se espera que estejam envolvidos, o programa pode ser dividido em vários níveis de competência. Por exemplo:

- *Level 0*: Completou todos os treinamentos obrigatórios de conscientização de segurança em toda a empresa
- *Level 1*: Completou todo o treinamento do tópico principal
- *Level 2*: Completou todo o treinamento específico da plataforma
- *Level 3*: Mais de 6 meses de experiência ativa como Security Champions / atendeu aos KPIs estabelecidos

Ao atribuir responsabilidades de acordo com diferentes níveis de maturidade, a precisão e o senso de engajamento podem ser aumentados. Além disso, proporciona uma visão mais clara do estado de maturidade do próprio programa.

## 6. Manter o interesse

Para ter um ecossistema contínuo e bem-sucedido de Security Champions, é crucial apoiá-los constantemente e fornecer materiais de aprendizagem. Abaixo estão várias maneiras de manter os campeões interessados e ajudá-los a evoluir como profissionais de segurança.

## 6.1 Workshops e treinamentos

Realize workshops periódicos para as equipes, explique a estratégia, promova as melhores práticas ou apenas compartilhe algumas notícias recentes do mundo da segurança. Organize um [quiz interativo](https://kahoot.com/), anuncie o Hacker Thursday ou inicie um "Bug Month". Converse com os Security Champions e juntos escolham qual formato é o mais adequado para você. Não importa o formato que você escolher, é provavelmente o ponto mais importante de todo o Playbook. Mantenha-os motivados e você será agradavelmente surpreendido muito em breve!

## 6.2 Torneios e concursos

Deixe os Security Champions praticarem desafios emocionantes por meio de concursos e hackathons. Um CTF interno trimestral pode ser facilmente configurado usando o [CTFd](https://github.com/CTFd/CTFd), ou você pode escolher um evento externo do [CTF Time](https://ctftime.org/).
Os dias de hacking também podem ser interessantes, seja para encontrar ou corrigir vulnerabilidades. Além de úteis e divertidos, esses eventos também podem ajudar a estabelecer uma linha de base da maturidade do campeão. As fraquezas identificadas podem ser abordadas em sessões de treinamento.
Não subestime o poder dos SWAGs para aumentar as taxas de engajamento!

## 6.3 Boletins informativos - regulares

Compartilhe notícias recentes de segurança por meio de canais de comunicação estabelecidos (como as [compilações semanais do appsec da Ezine](https://github.com/Simpsonpt/AppSecEzine)). Além disso, inicie boletins de segurança mensais com atualizações da equipe, planos, agradecimentos pelo bom trabalho e qualquer outra informação relevante e interessante - isso não apenas envolverá ainda mais os Security Champions, mas também será um bom ponto de verificação, também para sua segurança.

## 6.4 Canto dos campeões de segurança

Crie um espaço separado em seu wiki interno e adicione páginas dedicadas, como:

- calendário da conferência ([comece aqui](https://infosec-conferences.com/))
- biblioteca de segurança de bons livros e artigos ([comece aqui](https://github.com/paragonie/awesome-appsec))
- slides de conferências assistidas (ou [comece aqui](https://github.com/PaulSec/awesome-sec-talks))
- "salas para ideias e melhorias"

## 7. Posfácio

Se você seguiu todas as etapas, já deve ter um programa Security Champions funcionando. Tentei delinear as fases mais importantes para alcançar os melhores resultados, embora possa ser possível conseguir o mesmo saltando ou reordenando as fases.

A melhor coisa sobre o ecossistema Security Champions não é apenas a escalabilidade, mas os "benefícios colaterais" que sua organização está obtendo, sendo o principal o desenvolvimento de uma cultura de segurança. Com o tempo, eles começarão a propor suas próprias iniciativas, participando de P&D (pesquisa e desenvolvimento) e realizando workshops específicos de produtos, engajando cada vez mais pessoas e tornando a segurança "negócio de todos" como deveria ser.

Espero que tenha sido útil para você e ficaria grato se você enviasse seus comentários e propostas de melhoria como perguntas ou diretamente para alexander[at]antukh.com.

