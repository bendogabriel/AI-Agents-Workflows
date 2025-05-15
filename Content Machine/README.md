# Comentários do YouTube → Ideias de Conteúdo (via GPT-4 + Make + Apify)

Este projeto automatiza a coleta e análise de comentários do YouTube para gerar ideias de conteúdo usando inteligência artificial.

## 🔧 Tecnologias utilizadas
- [Apify](https://apify.com/) — scraping dos comentários
- [Make.com](https://make.com) — orquestração da automação
- [OpenAI GPT-4.1](https://platform.openai.com/) — análise dos comentários
- [Google Sheets] (https://sheet.new) — armazenamento de dados

## ⚙️ Funcionamento

1. O Apify coleta os comentários de vídeos específicos no YouTube.
2. O Make recebe os dados, filtra comentários muito curtos ou irrelevantes.
3. Um iterator envia os comentários individualmente para o GPT.
4. O GPT responde em JSON dizendo se há ou não ideia de conteúdo.
5. As respostas são armazenadas em uma planilha, banco ou outro destino.

## 📥 Exemplo de input:

```json
{
  "tituloVideo": "INTELIGÊNCIA EMOCIONAL: O que é, Benefícios e Como Desenvolver | Daniel Goleman",
  "comment": "Tenho 16 anos e sempre busco conhecimento."
}
```

## 📤 Exemplo de output:

![image](https://github.com/user-attachments/assets/40b7cf4e-5cec-4119-aa7a-d17d40667695)

![image](https://github.com/user-attachments/assets/13c32494-f755-481f-aa9f-2579a6d176ed)


```json
{
  "status": true,
  "ideiaConteudo": [
    "Como desenvolver inteligência emocional aos 16 anos?",
    "O que é inteligência emocional na adolescência?"
  ]
}
```
### 📌 Entre em contato para personalização e implementação!
<div> 
  <a href="https://github.com/bendogabriel" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/gabriel-bendo" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/agencianexateam" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="mailto:gmbendo14@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.nexateam.com.br/homenexa" target="_blank"><img src="https://github.com/user-attachments/assets/d0c56062-1934-42ff-8712-514f7072d5f8" width="35px" height="30px"></a>

</div>
