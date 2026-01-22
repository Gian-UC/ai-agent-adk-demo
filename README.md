# AriaAgent

![GitHub repo size](https://img.shields.io/github/repo-size/Gian-UC/ai-agent-adk-demo)
![GitHub last commit](https://img.shields.io/github/last-commit/Gian-UC/ai-agent-adk-demo)
![GitHub issues](https://img.shields.io/github/issues/Gian-UC/ai-agent-adk-demo)
![GitHub stars](https://img.shields.io/github/stars/Gian-UC/ai-agent-adk-demo?style=social)
![License](https://img.shields.io/github/license/Gian-UC/ai-agent-adk-demo)

AriaAgent é uma assistente virtual avançada desenvolvida para ajudar usuários em diversas tarefas, desde responder perguntas até fornecer recomendações personalizadas. Utiliza modelos de IA de última geração e integrações modernas para proporcionar uma experiência inteligente, amigável e eficiente.

## ✨ Funcionalidades
- Respostas inteligentes e contextualizadas
- Recomendações personalizadas
- Integração com Google ADK e Gemini
- Fácil configuração e extensão

## 🚀 Instalação

Requisitos:
- Python >= 3.10

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/Gian-UC/ai-agent-adk-demo.git
cd ai-agent-adk-demo
pip install -r requirements.txt  # ou use o pyproject.toml com poetry/pdm
```

## 🛠️ Uso

Exemplo de inicialização do agente:

```python
from Aria.agent import root_agent

response = root_agent.run("Olá, Aria! O que você pode fazer?")
print(response)
```

## 📁 Estrutura do Projeto

```
AriaAgent/
├── Aria/
│   ├── __init__.py
│   └── agent.py
├── video/
├── pyproject.toml
├── README.md
└── ...
```

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

Desenvolvido por [Gian-UC](https://github.com/Gian-UC) 🚀
