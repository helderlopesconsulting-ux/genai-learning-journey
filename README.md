# 🚀 Helder AI Notes

> Jornada de aprendizado em IA Generativa e Agentes Corporativos.

# genai-learning-journey
Repositório pessoal para registrar aprendizados, experimentos e referências sobre Inteligência Artificial, Agentes, Gemini e Vertex AI.

## 🎯 Objetivo

Construir uma base de conhecimento própria com:

- Conceitos estudados
- Labs concluídos
- Arquiteturas de referência
- Casos de uso corporativos
- Comandos úteis
- Insights aplicáveis ao trabalho

---

## 📚 Trilhas de Estudo

### IA Generativa
- Gemini
- Gemini Enterprise
- Vertex AI

### Agentes
- Agent Runtime
- Vertex AI Agent Engine
- Google ADK
- MCP (Model Context Protocol)
- Multi-Agent Systems
- Agent-to-Agent (A2A)

---

## 🧪 Labs Concluídos

| Data | Lab | Status |
|--------|----------|---------|
| 2026-11 | Add Agents to Gemini Enterprise | ✅ |
| 2026-11 | Gemini Enterprise | ✅ |
| 2026-11 | OAuth Configuration | ✅ |
| 2026-11 | Agent Runtime Deployment | ✅ |

---

## 📝 Principais Conceitos

### Agent Runtime

Ambiente onde o agente é executado e realiza suas ações.

Fluxo:

```text
Usuário
   ↓
Gemini
   ↓
Agent Runtime
   ↓
Ferramentas / APIs
   ↓
Resposta
```

### OAuth

Mecanismo padrão de autorização.

Permite que aplicações acessem recursos em nome do usuário sem expor senhas.

Exemplo:

```text
Usuário
   ↓
Google Identity
   ↓
Token OAuth
   ↓
Aplicação
```

### Gemini Enterprise

Versão corporativa do Gemini com:

- Governança
- Segurança
- Controle de acesso
- Integração com dados internos
- Integração com agentes

---

### Vertex AI Agent Engine

Plataforma para criar, publicar e executar agentes de IA.


## 📂 Estrutura do Repositório

```text
genai-learning-journey/
│
├── README.md
├── labs/
├── gemini/
├── vertex-ai/
├── agentes/
├── adk/
├── mcp/
└── arquiteturas/
```

## 🎓 Próximos Estudos

- MCP
- RAG
- Function Calling
- Agent-to-Agent (A2A)
- AI Product Management
- AI Governance
- Synthetic Personas
- Multi-Agent Systems
---

# Conceitos Importantes

## Agent Runtime

Ambiente onde um agente executa suas funções.

Responsabilidades:

- Receber solicitações
- Processar contexto
- Orquestrar ferramentas
- Consultar APIs
- Produzir respostas

Fluxo:

Usuário → Gemini → Agent Runtime → Sistemas → Resposta

---

## OAuth

Padrão de autorização que permite acesso seguro sem compartilhar senhas.

Fluxo:

Usuário → Google Identity → Token → Aplicação

Benefícios:

- Segurança
- Controle de acesso
- Auditoria
- Menor exposição de credenciais

---

## Gemini Enterprise

Versão corporativa do Gemini.

Principais capacidades:

- Controle empresarial
- Governança
- Integração com dados internos
- Integração com Agentes
- Segurança corporativa

---

## Vertex AI Agent Engine

Plataforma para criação e execução de agentes corporativos.

Capacidades:

- Deploy de agentes
- Escalabilidade
- Observabilidade
- Integração com ferramentas
- Gestão do ciclo de vida

---

## Integração de Agentes Corporativos

Permite conectar IA aos sistemas da organização.

Exemplos:

- Jira
- Azure DevOps
- SAP
- Salesforce
- BigQuery
- Databricks
- APIs internas

Arquitetura típica:

Gemini Enterprise
↓
Agent Engine
↓
Agent Runtime
↓
Tool Calling
↓
Sistemas Corporativos

---

---

## 👨‍💻 Autor

Helder Lopes

Especialista em Agilidade de Negócios

Estudos focados em:
- IA Generativa
- Agentes Corporativos
