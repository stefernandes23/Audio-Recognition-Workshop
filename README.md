# 🎤 Audio Recognition Workshop – QuantumFinance
## Projeto Final - (8DTSR)

# 🤖 Atendimento por Voz com Python

Este projeto foi desenvolvido para a disciplina Cognitive Environments no curso de MBA em Data Science e Inteligência Artificial. O objetivo é dar voz ao atendimento digital da QuantumFinance, permitindo que o cliente interaja por voz e não apenas por texto.

🎯 Objetivo  
Implementar um sistema de atendimento telefônico simulado que:

- Vocaliza frases pré-determinadas para saudar o cliente e oferecer opções
- Captura o áudio do cliente e reconhece a opção selecionada por meio de Speech To Text (STT)
- Confirma a opção escolhida com áudios de resposta sintetizados via Text To Speech (TTS)
- Permite interação contínua em loop até que o cliente escolha sair do atendimento

📝 Requisitos Detalhados  

| Requisito | Descrição |
|-|-|
| Frases pré-gravadas | Gerar áudios com TTS para: identificação da empresa, saudação e opções (1) Consulta ao saldo, (2) Simulação de compra internacional, (3) Falar com atendente, (4) Sair |
| Loop de atendimento | Executar áudios das opções em loop, capturar áudio do usuário, identificar palavra-chave da opção escolhida (não só números) e tocar resposta correspondente |
| Tratamento de erro | Caso nenhuma opção seja reconhecida, tocar áudio de erro e repetir as opções |
| Encerramento | Finalizar o loop quando o usuário escolher “Sair do atendimento” |

🧰 Tecnologias Utilizadas  
- **pyttsx3** – Geração de voz (Text To Speech)  
- **SpeechRecognition** – Reconhecimento de voz (Speech To Text)  
- **pygame** – Reprodução dos arquivos de áudio  
- **Python** – Orquestração da lógica do atendimento  
- **Jupyter Notebook** – Desenvolvimento e testes

🔍 Fluxo do Atendimento  

1️⃣ Saudações e opções são tocadas em áudio, geradas previamente com TTS.  
2️⃣ O sistema captura o áudio do usuário e converte em texto.  
3️⃣ Verifica a presença de palavras-chave das opções (exemplo: “saldo”, “simulação”, “atendente”, “sair”).  
4️⃣ Toca o áudio de resposta correspondente para confirmar a escolha.  
5️⃣ Caso não reconheça, toca áudio de erro e repete as opções.  
6️⃣ O loop continua até que o usuário diga “sair”.

🎯 Resultados

![Resultado de uma execução](https://github.com/user-attachments/assets/eb16fabd-4485-4483-95d9-5ed55a096b3c)



# Alunos 👨‍🎓👩‍🎓

1. André Leone 
2. Igor Alves 
3. Latife Neamen 
4. Stephanie Fernandes 
 

