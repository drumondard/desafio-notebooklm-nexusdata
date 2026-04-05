# Desafio Prático: Assistente Especializado com NotebookLM 🚀

Este repositório contém a entrega do desafio prático de criação de um assistente de IA especializado utilizando o **Google NotebookLM**. O projeto simula a estruturação de um produto real de engenharia de dados e a configuração de um agente de IA de alta performance.

## 📦 Produto: NexusData Pro
O **NexusData Pro** é uma solução de Data-as-a-Service (PaaS) focada na automação de pipelines de dados para o Google BigQuery. O objetivo do assistente é atuar como suporte técnico sênior, garantindo precisão e integridade nas informações prestadas aos usuários.

## 🛠️ Conteúdo do Repositório
Conforme os requisitos do desafio, este repositório contém exclusivamente:

1.  **[Documentacao_NexusData_Pro.pdf](./Documentacao_NexusData_Pro.pdf):** Manual de especificação técnica, funcionalidades, planos e limitações do produto.
2.  **[Prompt_Configuracao_Assistente.pdf](./Prompt_Configuracao_Assistente.pdf):** Documento contendo as diretrizes de comportamento do assistente, utilizando técnicas de:
    * **Role Prompting:** Definição de persona técnica sênior.
    * **Chain of Thought (CoT):** Instruções para raciocínio lógico passo a passo.
    * **Few-Shot:** Exemplos práticos de interações permitidas e restritas.

## 🧠 Técnicas de Engenharia de Prompt Utilizadas
Para garantir a confiabilidade do assistente, foram aplicadas camadas de segurança no prompt:
* **Grounding Estrito:** A IA está restrita apenas às informações do PDF fornecido.
* **Fallback Transparente:** Instrução clara para redirecionamento ao suporte humano (e-mail oficial) em caso de dúvidas fora de escopo.

---
**Autor:** Alexandre R Drumond
**Contexto:** MBA em Inteligência Artificial e Automação.
