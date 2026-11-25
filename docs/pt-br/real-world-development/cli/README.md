---
slug: pt-br/real-world-development/cli
title: "CLI do GitHub Copilot"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

O **[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** coloca o GitHub Copilot no seu terminal como um assistente de programação baseado em agentes. Ele explora bases de código, gera código, executa comandos e se conecta a ferramentas externas — tudo pela linha de comando, para que você mantenha o foco sem trocar para um editor gráfico.

Ao longo destas lições, você instalará e autenticará o Copilot CLI, depois fornecerá contexto do projeto com instruções personalizadas antes de usar o modo plan para gerar um recurso de forma deliberada. Você conectará o servidor MCP do Playwright para testar esse recurso em um navegador real e, em seguida, ampliará o Copilot com skills de agente reutilizáveis e agentes personalizados. Por fim, você explorará comandos de barra para gerenciar contexto, modelos e compartilhamento, e concluirá com uma revisão do que criou. Você também pode seguir uma [série opcional de três módulos com GitHub Copilot CLI e Foundry][foundry] para preparar um modelo, criar e implantar um agente hospedado e integrá-lo ao site.

## Lições

| Lição | Tópico | Descrição |
|----------|-------|-------------|
| [0. Pré-requisitos][ex0] | Configuração | Crie seu repositório e seu codespace |
| [1. Instalar o Copilot CLI][ex1] | Instalação | Instale e autentique o Copilot CLI |
| [2. Adicione avaliações com estrelas: um primeiro passo rápido][ex2] | Primeira alteração | Exiba as avaliações existentes e o valor alternativo quando forem nulas; depois, mescle seu primeiro PR |
| [3. Modos do agente: Plan e Autopilot][ex3] | Modos do agente | Planeje o recurso a partir da issue, crie-o com Autopilot e revise-o no modo Interactive |
| [4. Oriente o Copilot com instruções personalizadas][ex4] | Contexto | Explore e atualize as instruções e aplique-as à filtragem |
| [5. Personalize e use uma skill quality-checks][ex5] | Verificações reutilizáveis | Explore a skill existente, altere o formato do relatório e execute-a |
| [6. Valide a funcionalidade com o Playwright MCP][ex6] | Observação no navegador | Configure o MCP na CLI e inspecione o comportamento da filtragem |
| [7. Crie e use um agente de QA][ex7] | Requisitos e cobertura | Crie e selecione um perfil especializado e reúna as evidências finais de verificação |
| [8. Crie e mescle o PR do recurso][ex8] | Revisão e mesclagem | Revise a alteração completa, crie o PR e use o Agent Merge |
| [9. Comandos de barra no GitHub Copilot CLI][ex9] | Recursos da CLI | Explore contexto, modelos, compartilhamento e delegação opcional para o agente na nuvem |
| [10. Recapitulação e próximas etapas][ex10] | Resumo | Revise o fluxo de trabalho, as personalizações reutilizáveis e outros recursos |
| [Opcional: Incorpore o Foundry][foundry] | Agentes hospedados | Prepare um modelo, crie e implante um Backer Concierge baseado no catálogo e conecte-o ao site |

## Pré-requisitos

Antes de participar deste workshop, verifique se você tem:

- [ ] Uma conta do GitHub com um plano ativo **Copilot Student, Pro, Pro+, Business ou Enterprise**
- [ ] Familiaridade básica com operações de terminal e linha de comando
- [ ] O Git instalado e configurado

> [!TIP]
> Não tem um plano pago? Estudantes verificados podem obter o GitHub Copilot gratuitamente por meio do [GitHub Education][callout-student-plan-education]. O plano **Copilot Student** inclui os recursos de agente, MCP, revisão de código e Copilot CLI usados neste workshop. Portanto, você pode concluir todos os percursos com esse plano.

> [!NOTE]
> Se você usa o Copilot Business ou o Copilot Enterprise, verifique se o administrador habilitou o Copilot CLI para uso.

## Começar

[**Comece pela Lição 0: Pré-requisitos →**][ex0]

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[foundry]: 8-foundry-agent/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[callout-student-plan-education]: https://github.com/education/students
