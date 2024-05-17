O site [Anki](https://ankiweb.net/) é muito utilizado por concurseiros para decorar conteúdos de concursos.
Ele funciona com um sistema de baralhos e cards.
Um baralho é um tema que você deseja estudar. Exemplo: Scrum
E um card é cada assunto dentro do baralho que você precisa estudar.

Pegando o baralho Scrum como exemplo, digamos que você deseja decorar quais são os prazos dos eventos do Scrum (Sprint Planning, Sprint Retrospective e Sprint Review).
Com o baralho Scrum já criado, você pode adicionar um card para cada tópico que deseja aprender.
Sendo assim, um exemplo de card desse baralho Scrum seria:

Frente do card: "Qual é o prazo da reunião Sprint Planning no Scrum e qual a sua duração?"
Verso do card:
"A duração da Sprint Planning depende da duração da Sprint.
A regra geral é que para uma Sprint de quatro semanas, a Sprint Planning deve durar até oito horas.
Para Sprints mais curtas, a reunião deve ser proporcionalmente menor.

A reunião de Sprint Planning é geralmente dividida em duas partes:

Definir o que será feito (o que)

O Product Owner apresenta os itens do Backlog do Produto que são prioritários.
A equipe de desenvolvimento discute e seleciona os itens que podem ser completados na próxima Sprint, criando o Sprint Backlog.
Definir como será feito (como)

A equipe de desenvolvimento detalha os itens do Sprint Backlog e planeja como irá realizar o trabalho, dividindo as tarefas e estimando o esforço necessário."

O objetivo deste teste é que você leia os dados da planilha dados.xlsx, e para cada sheet, crie um baralho, e para cada baralho, adicione todas as linhas contendo a pergunta e a resposta do respectivo card.

**Diferencial 1**: Utilize Docker com todas as dependências necessárias. PHP, Selenium.

**Diferencial 2**: Documente o passo a passo para rodar o projeto.

**Diferencial 3**: Não deixe o usuário e senha do Anki mockado no código, utilize variáveis de ambiente no arquivo Dockerfile.
