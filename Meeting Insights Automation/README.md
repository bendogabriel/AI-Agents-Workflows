# 🤖 Automação de Reuniões com IA (Fireflies + Gemini + ClickUp)

Este projeto automatiza o ciclo completo de uma reunião, desde a transcrição até a análise estratégica e documentação em tarefas.

## 🔗 Tecnologias Utilizadas

- [Fireflies.ai](https://fireflies.ai) – Grava e transcreve automaticamente as reuniões
- [Google Vertex AI - Gemini Pro](https://cloud.google.com/vertex-ai/docs/generative-ai) – Analisa a transcrição com LLM
- [ClickUp](https://clickup.com) – Armazena o relatório final como tarefa documentada
- [n8n](https://n8n.io) – Orquestra toda a automação

---

## ⚙️ Funcionalidade

1. 🎙️ **Fireflies** grava a reunião e gera a transcrição.
2. 🔍 O N8N coleta a transcrição via GraphQL.
3. 🧠 **Gemini (LLM da Google)** recebe a transcrição e retorna um relatório estruturado em JSON.
4. 🧾 Um Function Node extrai `title` e `output` do JSON gerado.
5. 📌 **ClickUp** cria uma tarefa com o título da reunião e o relatório como descrição.

---

## 📝 Exemplo de Output

```json
{
  "title": "Análise da Demonstração do Agente de IA para Contabilidade",
  "content": "### Relatório Estratégico\n\n- Resumo da reunião\n- Decisões tomadas\n- Tarefas inferidas\n- Insights e próximos passos..."
}
```
<img width="1405" height="499" alt="image" src="https://github.com/user-attachments/assets/b7aeb319-35c0-45d1-a57d-ccadeeb7fe7d" />

### 📌 Contribuição
Sinta-se à vontade para sugerir melhorias ou abrir Issues!

### 📌 Entre em contato para personalização e implementação!
<div> 
  <a href="https://github.com/bendogabriel" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/gabriel-bendo" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/agencianexateam" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="mailto:gmbendo14@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.nexateam.com.br/homenexa" target="_blank"><img src="https://github.com/user-attachments/assets/d0c56062-1934-42ff-8712-514f7072d5f8" width="35px" height="30px"></a>

</div>
    
