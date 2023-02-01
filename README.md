# Desafio-Ifood

# Sprint Challenge: React e Node.js (ou outra ferramenta de sua preferencia) - `Autenticação` e `Listagem de Produtos`

## Descrição

Neste desafio, você projeta e cria um DASBOARD para lojas do IFOOD via API para gerenciar os seguintes recursos: `Autenticação` e `Listagem de Produtos`.

## API IFOOD DOCUMENTAÇÃO

https://developer.ifood.com.br/pt-BR/docs/references#authentication

## Instruções

**Leia atentamente estas instruções**. Entenda exatamente o que é esperado **_antes_** de começar a codificar.

Esta é uma avaliação individual, por favor, trabalhe nela sozinho. É uma oportunidade de demonstrar proficiência dos conceitos e objetivos introduzidos e praticados nos dias anteriores.

Se as instruções não estiverem claras, contate-nos.

O Produto Mínimo Viável deve ser concluído em quatro horas.

Siga estas etapas para configurar e trabalhar em seu projeto:

- [ ] Crie uma cópia bifurcada deste projeto.
- [ ] Adicione nós como colaborador no Github.
- [ ] Clone sua versão bifurcada do Repositório.
- [ ] Crie uma nova ramificação no clone: git checkout -b `firstName-lastName`.
- [ ] Implementar o projeto nesta Filial, efetuando alterações regularmente.
- [] Push commits: git push origin `firstName-lastName`.

Siga estas etapas para concluir seu projeto.

- [] Envie uma solicitação pull para mesclar a ramificação `firstName-lastName` com `main` em **seu fork, não faça solicitações pull no repositório do**.
- [ ] Por favor, não mescle sua própria solicitação pull.
- [ ] Adicione-nos como um revisor na solicitação pull
- [ ] Nós contará o desafio como concluído ao mesclar o branch em `main`.

## Confirma

Confirme seu código regularmente e use mensagens descritivas. Isso ajuda você (no caso de precisar retornar ao código antigo) e seu líder de equipe.

## Auto-estudo/Questões dissertativas

Demonstre sua compreensão dos conceitos deste Sprint respondendo às seguintes perguntas de forma livre. Edite este documento para incluir suas respostas após cada pergunta. Certifique-se de deixar uma linha em branco acima e abaixo de sua resposta para que seja clara e fácil de ser lida pelo seu líder de equipe.

- [ ] Entendimento de API e Authentication.

- [ ] Descrever como funciona?

- [ ] Descrever um Recurso?

- [ ] O que a API pode retornar para ajudar os clientes a saber se uma solicitação foi bem-sucedida?

- [ ] Como podemos particionar nosso aplicativo em subaplicativos?

## Produto com minima viabilidade

- [ ] Configure um script _npm_ chamado _"servidor"_ que executará seu código usando _nodemon_. Faça _nodemon_ ser apenas uma dependência de tempo de desenvolvimento, não deve ser implantado na produção.
- [ ] Configure um script _npm_ chamado _"start"_ que executará seu código usando _node_.

Projetar e construir os endpoints necessários para:

- [ ] Execute operações CRUD em _projects_ e _actions_. Ao adicionar uma ação, certifique-se de que o `project_id` fornecido pertence a um `project` existente. Se você tentar adicionar uma ação com um `id` de 3 e não houver nenhum projeto com esse `id`, o banco de dados retornará um erro.
- [ ] Recupera a lista de ações de um projeto.

Leia as seções a seguir antes de implementar o Produto Mínimo Viável, elas descrevem como o banco de dados está estruturado e os arquivos e métodos disponíveis para interagir com os dados.

**Ignore todos os avisos do terminal sobre return() não suportados pelo SQLite.**

## Alcançar meta

- Criar sistema de login e autenticação
- No aplicativo React, mostre uma lista de todos os _produtos atraves da chamada da API do IFOOD para loja
- Adicionar funcionalidade para mostrar os detalhes de um projeto, incluindo suas ações, ao clicar no nome de um projeto na lista. Use o React Router para navegar para uma rota separada para mostrar os detalhes do projeto.
- Adicionar estilo! (opcional)
