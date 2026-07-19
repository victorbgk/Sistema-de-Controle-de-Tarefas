# Sistema de Controle de Tarefas

Sistema criado com objetivo de ajudar a organizar as tarefas do dia a dia.

## Sobre o projeto

O Sistema de Controle de Tarefas ajuda o usuário a cadastrar, organizar e acompanhar suas tarefas. Cada tarefa pode ter uma categoria e uma prioridade, o que facilita achar o que precisa ser feito e evita esquecer compromissos.

**Público-alvo:** pessoas que querem organizar suas tarefas diárias de um jeito simples.

**Problema que resolve:** dificuldade em lembrar e organizar as tarefas pendentes.

## Objetivos

- Permitir login do usuário
- Criar, editar e excluir tarefas
- Organizar tarefas por categoria e prioridade
- Marcar tarefas como concluídas
- Buscar e filtrar tarefas

## Perfil de usuário

### Usuário
A pessoa que usa o sistema. Faz login e cuida das próprias tarefas: cria, edita, exclui, marca como concluída, organiza por categoria e pesquisa.

## Funcionalidades

- Login
- Criar tarefa
- Editar tarefa
- Excluir tarefa
- Marcar tarefa como concluída
- Pesquisar tarefas (por categoria e por prioridade)
- Gerenciar categorias

## Requisitos Funcionais (RF)

| ID | Requisito |
|---|---|
| RF01 | Como usuário, eu quero fazer login para acessar minhas tarefas com segurança. |
| RF02 | Como usuário, eu quero criar uma tarefa para registrar algo que preciso fazer. |
| RF03 | Como usuário, eu quero editar uma tarefa para atualizar prazo ou prioridade. |
| RF04 | Como usuário, eu quero excluir uma tarefa que não preciso mais. |
| RF05 | Como usuário, eu quero marcar uma tarefa como concluída para acompanhar meu progresso. |
| RF06 | Como usuário, eu quero pesquisar e filtrar tarefas por categoria ou prioridade. |
| RF07 | Como usuário, eu quero organizar minhas tarefas em categorias. |

## Requisitos Não Funcionais (RNF)

| ID | Requisito |
|---|---|
| RNF01 | O sistema deve responder às ações em no máximo 2 segundos. |
| RNF02 | As senhas dos usuários devem ficar protegidas (criptografadas). |
| RNF03 | O sistema deve funcionar nos navegadores Chrome, Firefox e Edge. |

## Diagrama de Casos de Uso

O diagrama está em [`docs/diagrama-casos-de-uso.svg`](docs/diagrama-casos-de-uso.svg).

Ele mostra:
- O ator **Usuário**
- A fronteira do sistema
- 7 casos de uso
- Relação `<<include>>`: todas as ações do usuário exigem login ("Autenticar Usuário")
- Relação `<<extend>>`: "Filtrar por Categoria" e "Filtrar por Prioridade" são opções extras de "Pesquisar Tarefas"

## Tecnologias utilizadas

- **Front-end:** HTML, CSS, JavaScript
- **Back-end:** Python (Flask)
- **Banco de dados:** SQLite

## Projeto desenvolvido por:

- Victor Gabriel Freire Andrade

## Como executar

> Preencher depois que o código estiver pronto (ex: instalação de dependências, comando para rodar o servidor, etc.).
