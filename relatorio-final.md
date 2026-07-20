# Relatório Final 
**Projeto:** Sistema de Controle de Tarefas

## 1. Capa e Papéis Scrum

* **Aluno:** Victor Gabriel Freire Andrade
* **Dinâmica da Equipe:** Este projeto foi desenvolvido individualmente. Para atender aos critérios da disciplina, atuei como uma "equipe de um homem só", concentrando todos os papéis do framework Scrum:
    * **Product Owner (PO):** Fui responsável por definir o escopo inicial, validar quais funcionalidades eram essenciais (baseado nos requisitos) e priorizar a lista de tarefas.
    * **Scrum Master (SM):** Fiquei encarregado de configurar o GitHub Projects (Kanban), definir as *labels*, criar os *Milestones* e garantir que o fluxo de trabalho não travasse.
    * **Developer:** Escrevi o código, elaborei o diagrama de casos de uso (UML) e redigi a documentação.
    * *Rodízio:* Não houve rodízio, dada a natureza individual do trabalho.

---

## 2. Diário de Bordo Ágil (Resumo das Sprints)

Como o projeto foi iniciado na quinta-feira (16/07) por volta das 14h e precisava ser entregue no fim de semana, adaptei o conceito de "Sprints de 1 semana" para **"Ciclos diários de trabalho"**. Essa adaptação me permitiu manter a cadência ágil dentro do tempo disponível.

* **Sprint 1 (Quinta-feira, 16/07 - Setup e Concepção):**
    * **Foco:** Criação do repositório, configuração do board Kanban no GitHub Projects (colunas: Backlog, To Do, In Progress, Review, Done) e elicitação dos Requisitos Funcionais e Não Funcionais.

* **Sprint 2 (Sexta-feira, 17/07 - Modelagem e Arquitetura):**
    * **Foco:** Desenvolvimento do Diagrama de Casos de Uso (UML) e criação da estrutura inicial do código (criação das classes principais).

* **Sprint 3 (Sábado, 18/07 - Funcionalidades Core):**
    * **Foco:** Mão na massa. Codificação intensa para garantir que os requisitos (como criar, editar, excluir e pesquisar tarefas) funcionassem.

* **Sprint 4 (Domingo, 19/07 - Entrega e Revisão Final):**
    * **Foco:** Testes finais do sistema, revisão geral e consolidação da documentação (README e este relatório).

---

## 3. Provas das Cerimônias e Retrospectiva (Adaptação Solo)

Aplicar os ritos do Scrum trabalhando sozinho exigiu adaptações práticas:

* **Sprint Planning:** Em vez de uma reunião com várias pessoas, minha *Planning* consistiu em sentar antes de abrir o editor de código, listar todas as tarefas como *Issues* no GitHub, aplicar as *labels* (feature, documentation) e colocá-las na coluna "To Do".
* **Daily Scrum (Check-in Pessoal):** Substituí a reunião diária por um hábito simples: toda vez que eu sentava para programar, olhava o GitHub Projects primeiro. Isso respondia às três perguntas da Daily: *O que eu fiz ontem?* (Olhava a coluna Done), *O que vou fazer hoje?* (Puxava algo do To Do para In Progress), *Há algum impedimento?* (Se houvesse, eu pesquisava a solução antes de codar).
* **Retrospectiva Sincera:**
    * **O que deu certo:** A ferramenta do GitHub Projects foi fundamental. Quando se trabalha sozinho com o prazo apertado, é muito fácil se perder e tentar fazer tudo ao mesmo tempo. O Kanban me forçou a terminar uma funcionalidade antes de começar outra.
    * **O que deu errado/Desafios:** O maior obstáculo foi o acúmulo de funções. Fazer o código e parar para atualizar a documentação ou mover os cards quebra um pouco o ritmo de raciocínio. Comecei acumulando algumas tarefas de mover cards, mas me forcei a fechar as *Issues* pelos *commits* (`Fixes #ID`) para automatizar o processo na reta final.
