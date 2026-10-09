## Sobre

Sou AI Engineer com foco em automação e desenvolvimento assistido por IA. Meu ambiente de trabalho é o Claude Code, configurado para que o agente trabalhe dentro de regras claras: guardrails e hooks validam o que ele faz, skills conduzem tarefas repetitivas por fluxos definidos e a orquestração de multiagentes e subagentes divide o trabalho entre agentes especializados.

No lado da automação, desenvolvo APIs REST em Python com FastAPI, integrações por webhook e pipelines de entrega com Docker, AWS e GitHub Actions.

Estudo Análise e Desenvolvimento de Sistemas no Unipê (4º período, conclusão em 12/2026). Fui Tech Lead de uma equipe de cinco pessoas num projeto acadêmico: backend REST em FastAPI com migrações Alembic e Docker, e revisão do código de backend da equipe. Inglês B2 (certificado Voxy, 12/2025).

## Como trabalho com IA

- *Guardrails e hooks* restringem e validam as ações do agente durante o desenvolvimento.
- *Skills* padronizam tarefas repetitivas e conduzem o agente por fluxos de trabalho definidos.
- *Multiagentes e subagentes* dividem uma tarefa entre agentes especializados.
- *Contexto versionado no repositório:* um AGENTS.md como fonte única de instrução para qualquer agente, decisões em decisions/, trabalho em andamento em specs/ e um log por sessão. Exemplo no [AGENTS.md do CoreDev](https://github.com/luciolimap/CoreDev/blob/main/AGENTS.md).

## Projetos em destaque

### [CoreDev](https://github.com/luciolimap/CoreDev) · em desenvolvimento

Hub desktop para quem desenvolve com o Claude Code: agente, GitHub e terminal numa única janela, amarrados ao projeto ativo.

- O objetivo é persistência de sessão de verdade: fechar o app no meio de uma conversa com o Claude Code e, ao reabrir, encontrar o mesmo layout, o mesmo scrollback e o mesmo diretório.
- Desenvolvido no próprio fluxo assistido por agentes, com instruções, decisões e histórico de sessão versionados no repositório.

Electron React TypeScript node-pty xterm.js

### [inbox-omnichannel](https://github.com/luciolimap/inbox-omnichannel)

Automação de atendimento multicanal: mensagens de Telegram, WhatsApp e e-mail chegam numa caixa de entrada única, o atendente responde na web e a resposta sai pelo mesmo canal.

- Gateway em Node/Fastify recebe os webhooks e traduz o payload de cada canal para um contrato interno único.
- Core em Java/Spring Boot com o domínio em PostgreSQL; idempotência por índice único no id exter
- Telegram real, com webhook validado por segredo; WhatsApp e e-mail por adapters simulados no mesmo contrato.
- Testes com Testcontainers e CI de cinco jobs no GitHub Actions.

Node.js TypeScript Fastify Java 21 Spring Boot PostgreSQL Docker

### [Aplicacoes-LLM](https://github.com/luciolimap/Aplicacoes-LLM)

11 aplicações web em Python e Streamlit, desenvolvidas com apoio de LLMs a partir de uma lista de exercícios. Cada uma tem app.py, requirements.txt e README próprios.

- Persistência local com SQLite e autenticação com senha protegida por hash.

Python Streamlit SQLite

## Outros projetos

- **[BankCore](https://github.com/luciolimap/BankCore):** núcleo bancário em microsserviços .NET via RabbitMQ, com saga coreografada, idempotência no consumer, 23 testes e 4 ADRs.

## Stack

- *IA e agentes:* Claude Code (guardrails, hooks, skills, multiagentes e subagentes) · LLMs · O
- *Automação e integração:* n8n · webhooks · APIs REST · GitHub Actions (CI)
- *Backend e dados:* Python · FastAPI · Alembic · Streamlit · Node.js · SQLite · PostgreSQL
- *DevOps:* Docker · AWS · Git · GitHub
- *Também nos projetos:* TypeScript · Java · Spring Boot · C# · .NET · RabbitMQ · Electron

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=luciolimap&show_icons=true&hide_border=true&theme=transparent" />

  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=luciolimap&layout=compact&hide_border=true&theme=transparent" />
</p>
