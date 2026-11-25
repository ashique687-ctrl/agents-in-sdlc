---
slug: es-es/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** incorpora GitHub Copilot a tu terminal como asistente de programación con agentes. Explora bases de código, genera código, ejecuta comandos y se conecta a herramientas externas, todo desde la línea de comandos, para que puedas mantener el flujo sin cambiar a un editor gráfico.

A lo largo de estos ejercicios instalarás y autenticarás Copilot CLI, y después le darás contexto del proyecto con instrucciones personalizadas antes de usar el modo de planificación para generar una funcionalidad de forma deliberada. Conectarás el servidor MCP de Playwright para probar esa funcionalidad en un navegador real y, a continuación, ampliarás Copilot con habilidades de agente reutilizables y agentes personalizados. Por último, explorarás los comandos de barra para gestionar el contexto, los modelos y el uso compartido, y terminarás con un repaso de lo que has creado. También puedes seguir una [serie opcional de tres módulos con GitHub Copilot CLI y Foundry][foundry] para preparar un modelo, crear y desplegar un agente hospedado e integrarlo en el sitio.

## Ejercicios

| Ejercicio | Tema | Descripción |
|----------|-------|-------------|
| [0. Requisitos previos][ex0] | Configuración | Crea tu repositorio y tu codespace |
| [1. Instalación de Copilot CLI][ex1] | Instalación | Instala y autentica Copilot CLI |
| [2. Añade valoraciones con estrellas: un primer cambio][ex2] | Primer cambio | Muestra las valoraciones existentes y el valor alternativo para los valores nulos; después, combina tu primer PR |
| [3. Modos del agente: Plan y Autopilot][ex3] | Modos del agente | Planifica la funcionalidad a partir de su incidencia, créala con Autopilot y revísala en modo Interactive |
| [4. Guía a Copilot con instrucciones personalizadas][ex4] | Contexto | Explora y actualiza las instrucciones y aplícalas al filtrado |
| [5. Personaliza y usa una aptitud quality-checks][ex5] | Comprobaciones reutilizables | Explora la aptitud existente, cambia el formato del informe y ejecútala |
| [6. Valida la funcionalidad con Playwright MCP][ex6] | Observación en el navegador | Configura MCP en la CLI e inspecciona el comportamiento del filtrado |
| [7. Crea y usa un agente de control de calidad][ex7] | Requisitos y cobertura | Crea y selecciona un perfil especializado y recopila las pruebas finales de verificación |
| [8. Crea y combina la PR de la funcionalidad][ex8] | Revisión y combinación | Revisa el cambio completo, crea la PR y usa Agent Merge |
| [9. Comandos de barra en GitHub Copilot CLI][ex9] | Funciones de CLI | Explora el contexto, los modelos, el uso compartido y la delegación opcional al agente en la nube |
| [10. Resumen y próximos pasos][ex10] | Resumen | Repasa el flujo de trabajo, las personalizaciones reutilizables y otros recursos |
| [Opcional: incorpora Foundry][foundry] | Agentes hospedados | Prepara un modelo, crea y despliega el concierge y conéctalo al sitio web en tres módulos |

## Requisitos previos

Antes de asistir a este taller, asegúrate de tener:

- [ ] Una cuenta de GitHub con un plan activo de **Copilot Student, Pro, Pro+, Business o Enterprise**
- [ ] Conocimientos básicos de operaciones de terminal/línea de comandos
- [ ] Git instalado y configurado

> [!TIP]
> ¿No tienes un plan de pago? Los estudiantes verificados pueden obtener GitHub Copilot gratis a través de [GitHub Education][callout-student-plan-education]. El plan **Copilot Student** incluye las funciones de agente, MCP, revisión de código y Copilot CLI que utiliza este taller, así que puedes completar con él todos los recorridos.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Si usas Copilot Business o Copilot Enterprise, asegúrate de que tu administrador haya habilitado Copilot CLI.

## Primeros pasos

**[Empieza con el ejercicio 0: Requisitos previos →][ex0]**

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
