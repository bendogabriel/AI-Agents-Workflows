# 🧊 Cold Email Engine para Contabilidades

Automação completa de prospecção B2B focada em contabilidades, combinando scraping, geração de icebreakers personalizados e envios inteligentes com alta taxa de resposta.

## ⚙️ Stack Utilizada

- [Apollo.io](https://apollo.io) → Filtro e coleta de leads
- [Apify](https://apify.com) → Scraper de dados (nome, cargo, email, telefone, empresa)
- [Make.com](https://make.com) → Geração de icebreakers + atualização automática no Google Sheets
- [Google Sheets](https://sheets.google.com) → Base dinâmica de leads com enriquecimento
- [Instantly](https://instantly.ai) → Cold email em escala com variáveis {{dinâmicas}} e follow-up automático

## 🔁 Fluxo da Automação

1. **Pesquisa de Leads no Apollo**  
   - Segmentação: Escritórios de contabilidade
   - Exportação dos links dos perfis
  
![image](https://github.com/user-attachments/assets/59d4971d-25e2-4355-b010-31387ff55a40)

2. **Scraping com Apify**  
   - Extração dos dados em `.csv`: nome, cargo, email, telefone e empresa

3. **Icebreakers via Make.com**  
   - Geração de quebra-gelo com IA
   - Atualização da planilha com campos personalizados
  
![image](https://github.com/user-attachments/assets/13b9805a-1a5e-41d1-8911-5cad5b9178ed)

4. **Campanha no Instantly**  
   - Cold email com variáveis como `{{icebreaker}}`, `{{nome}}`, `{{empresa}}`
   - Follow-up automático configurado para leads que não responderam

  ![image](https://github.com/user-attachments/assets/78120b50-9122-4c17-97f3-3876e890b3d5)

## 🧠 Resultados Esperados

- Personalização em escala (sem parecer robótico)
- Aumento da taxa de abertura e resposta
- Economia de tempo no processo comercial
- Base replicável para outros nichos


## 📌 Exemplo de Icebreaker

> "Oi João, vi que você está à frente da Contábil Lima há mais de 8 anos — admiro negócios com tanta consistência! Tenho algo que pode agilizar ainda mais seu atendimento com IA."


## 🧰 Reutilizar este projeto

Você pode adaptar esse fluxo para qualquer nicho B2B. Basta trocar o filtro no Apollo e ajustar a copy dos emails.

### 📌 Entre em contato para personalização e implementação!
<div> 
  <a href="https://github.com/bendogabriel" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/gabriel-bendo" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/agencianexateam" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="mailto:gmbendo14@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.nexateam.com.br/homenexa" target="_blank"><img src="https://github.com/user-attachments/assets/d0c56062-1934-42ff-8712-514f7072d5f8" width="35px" height="30px"></a>

</div>
