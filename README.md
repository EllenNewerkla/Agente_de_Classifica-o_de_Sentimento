# Agente_de_Classifica-o_de_Sentimento
Trabalho sobre um Agente de Classificação de Sentimentos com Análise Automática de Texto usando a plataforma n8n onde as respostas são salvas em um Google Sheets.
### Objetivo: 
Receber um texto via Webhook e determinar o sentimento geral (positivo, negativo, neutro) e o tema principal. 
<br/>
Ferramentas: 
- Webhook
- AI Model (LLM)
- Code (pós-processamento)
- AI Agent
- Respond to Webhook
- **Desafio**: Salvar resultados em uma planilha do Google Sheets.

### Em caso do video não rodar, aqui está o link no Youtube para assistir: https://youtu.be/e_YqJ3IY2Jo?si=G1Yn4rfqvhRr2Dsf

## Fluxo de execução da aplicação:
<img width="1532" height="477" alt="Captura de tela 2025-11-28 235852" src="https://github.com/user-attachments/assets/fb05c076-ccc5-4125-94dd-5ce1559adc44" />

<br/>

## Planilha do Google Sheets
<img width="1005" height="459" alt="Captura de tela 2025-11-28 235907" src="https://github.com/user-attachments/assets/a20f333b-5962-4e93-b459-7fa17a95dafb" />

<br/>

## Comando para executar:
<br/>
`curl -X POST https://nelle.app.n8n.cloud/webhook-test/sentiment-classifier -H "Content-Type: application/json" -d "{\"texto\": \"O Filme me deu sono\"}"`

