**************   Desafio DIO Bradesco GenAI ****************
# Chat de Voz com OpenAI (Google Colab)

Este projeto implementa um chat de voz contínuo, onde o usuário fala pelo microfone e recebe respostas faladas, utilizando modelos da OpenAI.

O fluxo completo é:
Voz → Transcrição (Whisper) → Chat com memória → Voz (gTTS)

---

# Tecnologias utilizadas

- Python
- Google Colab
- Whisper (Speech-to-Text)
- OpenAI API (Chat)
- gTTS (Text-to-Speech)
- JavaScript (MediaRecorder API)



# Funcionalidades

- Conversa contínua com memória
- Entrada por voz
- Resposta por voz
- Encerramento por comando de voz (`sair`, `tchau`, etc.)
- Projeto seguro (API Key não exposta)


---

# Como executar no Google Colab

# Abrir o notebook
Abra o arquivo `.ipynb` no Google Colab.

---

# Configurar a chave da OpenAI
Nunca publique sua chave no GitHub

Em uma célula do Colab, execute:

python
import os
os.environ["OPENAI_API_KEY"] = "SUA_CHAVE_DA_OPENAI_AQUI"

## 📂 Estrutura do projeto
chat-voz-openai
├── chat_voz_openai.ipynb
└── README.md

Licença
Este projeto é livre para uso educacional e experimental.
Projeto desenvolvido para estudos e testes com IA Generativa, áudio e APIs da OpenAI.
Autor: Fernando Andrade
