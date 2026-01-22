
<p align="center">
	<img src="https://raw.githubusercontent.com/Gian-UC/ai-agent-adk-demo/main/banner.png" alt="AriaAgent Banner" style="max-width: 100%;">
</p>

# AriaAgent
<p align="center">
	<img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Python">
	<img src="https://img.shields.io/badge/Google%20ADK-%3E%3D1.22.1-blueviolet?logo=google" alt="Google ADK">
	<img src="https://img.shields.io/badge/Google%20Gemini-0.8.6-ffca28?logo=google" alt="Google Gemini">
	<img src="https://img.shields.io/badge/python--dotenv-1.2.1-44a833?logo=python" alt="python-dotenv">
</p>


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


## ▶️ Como rodar o projeto

1. Crie e ative o ambiente virtual:

	No Windows (cmd):
	```bash
	python -m venv .venv
	.venv\Scripts\activate
	```
	No PowerShell:
	```powershell
	.venv\Scripts\Activate.ps1
	```
	No Linux/Mac:
	```bash
	python3 -m venv .venv
	source .venv/bin/activate
	```

2. Instale as dependências:
	```bash
	pip install -r requirements.txt  # ou use poetry/pdm conforme preferir
	```

3. Configure as variáveis de ambiente:
	- Crie um arquivo `.env` dentro da pasta `Aria/` com suas chaves:
	  ```env
	  GOOGLE_API_KEY=SEU_TOKEN_AQUI
	  SEGURAIA_API_KEY=SEU_TOKEN_AQUI
	  ```


4. Execute a API (ADK Web):
	```bash
	adk web
	```

5. (Opcional) Execute o agente em modo interativo:
	```python
	from Aria.agent import root_agent
	response = root_agent.run("Olá, Aria! O que você pode fazer?")
	print(response)
	```

Você pode criar um script Python para interagir com a Aria, integrar em outros sistemas ou acessar a API via ADK Web.

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
