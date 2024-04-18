## Processo: SCRUM/XP

Tendo em vista que nosso projeto tem um conjunto de requisitos desconhecido, escolhemos uma abordagem ágil, e o processo escolhido é um misto de XP e SCRUM. A metodologia XP (Extreme Programming) é uma metodologia de desenvolvimento de software que se concentra na criação de software de alta qualidade, de maneira rápida e eficaz. Valoriza a simplicidade no design e na implementação, priorizando soluções simples e diretas. O XP é uma solução para projetos de software que tem requisitos voláteis, por conta de sua abordagem flexível, que permite a adaptação do desenvolvimento às mudanças. O framework de desenvolvimento de projetos SCRUM é uma forma de organizar o projeto em si e o trabalho em equipe, de forma que eles combinam. Detalharemos o raciocínio para a escolha nos tópicos mais abaixo.

​	


| Atividade                        | Método(s)                  | Ferramenta(s)     | Entrega                                       |
|----------------------------------|-------------------------|----------------|-----------------------------------------------|
| Elicitação e Descoberta          | Brainstorming;<br>Análise de personas;<br>Entrevistas;<br>Histórias e cenários;<br> | Discord;<br>Microsoft Teams;<br> | Lista de Requisitos Funcionais (RFs) e Requisitos Não-Funcionais (RNFs);<br>Lista de Personas;<br> |
| Análise e consenso  | Prototipação, negociação, brainstorming | Miro, Discord, Microsoft Teams | Lista refinada dos RFs e RNFs      |
| Declaração e representação | Divisão de requisitos em temas, épicos e user stories; <br> | Issues do Github;<br> | Especificação de Requisitos com temas, épicos e histórias de usuário;<br> |
| Verificação e Validação | Checklist de verificação e validação; <br>Obtenção de feedback do(s) cliente(s);<br>Obtenção de feedback da equipe;<br>Backlog DEEP;<br>DoR e DoD;<br> | Issues do Github;<br>Discord;<br>Microsoft Teams;<br> | DoR e DoD de cada requisito da sprint;<br>Backlog do Produto no padrão DEEP;<br> |
| Organização e atualização | Priorização utilizando a técnica MoSCoW;<br> | Issues do Github;<br> | Backlog do produto priorizado;<br> |


## Explicação detalhada da escolha do processo

### Abordagem de Desenvolvimento: Ágil

Com base na série de questionamentos propostos por Sommerville (2019), a escolha da abordagem ágil é fundamentada nas características iniciais do projeto. Conforme vistas abaixo:

- Requisitos não conhecidos na sua totalidade.
- Prazo de entrega já definido.
- Falta de verba inicial.
- Entrega incremental de funcionalidades em prazos mais curtos.

### Ciclo de vida: Iterativo e Incremental

Como os requisitos são incertos, provavelmente teremos que voltar em alguns durante o projeto, para assegurar a confiança e segurança para o cliente final. Ademais, não são conhecidas todas as exigências do cliente, portanto é importante a proximidade para consultas e mudanças mais rápidas. A escolha de um ciclo de vida iterativo e incremental proporciona uma maior flexibilidade no desenvolvimento baseado no surgimento ou alteração de requisitos, além do envolvimento com o cliente buscando feedback contínuo.


## Abordagem de Desenvolvimento do Software: framework Sommerville

De base com a abordagem do framework Sommerville, optamos responder as perguntas classificadas em 3 temas. 

Questões técnicas conectadas ao sistema que será desenvolvido.
Questões humanas conectadas à equipe que cuidará do desenvolvimento
Questões de organização conectadas às condições do ambiente que será desenvolvido a aplicação.

### Questões técnicas:

**Qual o tamanho do software que será desenvolvido?**

 - Um sistema de pequeno porte.

**Qual modelo de software será desenvolvido?**

- Uma aplicação web, de média complexidade e com requisitos pouco conhecidos.

**Qual a vida útil prevista para o software?**

- Por hora, vida útil, médio a longo período

**O sistema está sujeito a controle externo?**

- Sim, sujeito ao controle dos corretores e o acompanhamento dos clientes dos seguros

### Questões Humanas:

**Qual o nível técnico da equipe responsável pelo desenvolvimento?**

- A equipe possui conhecimentos em desenvolvimento web front-end, desenvolvimento de APIs e gerenciamento e modelagem de bancos de dados.

**Como está organizado o time de desenvolvimento?**

- A equipe foi dividida em front-end e back-end.

**Quais são as tecnologias disponíveis para apoiar o desenvolvimento do sistema?**

- Frameworks de desenvolvimento front-end (no caso, React) e back-end (Java, com o framework Spring).

### Questões organizacionais:

**É importante ter uma especificação e um projeto (design) bem detalhados antes de passar para a implementação — talvez por motivos contratuais?**

- Não, algumas partes da aplicação podem ser concluídas sem especificações de design.

**É realista uma estratégia de entrega incremental, na qual o software é entregue aos clientes ou outros stakeholders e um rápido feedback é obtido?**

- Sim. Este método permite resolver problemas locais que podem afetar todo o produto antes da implementação completa do projeto.

**Os representantes do cliente estarão disponíveis e dispostos a participar do time de desenvolvimento?**

- Não, os representantes, estarão apenas disponíveis para dar feedbacks, durante o processo, mas não participando do desenvolvimento em si.

**Existem questões culturais que possam afetar o desenvolvimento do sistema?**

- Não, como o time está iniciando, não está vinculada a uma metodologia específica de desenvolvimento.
