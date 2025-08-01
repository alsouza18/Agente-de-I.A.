# 🤖 Buster - Assistente Inteligente

O **Buster** é um assistente inteligente desenvolvido em Python para ajudar estudantes de Ciência da Computação e professores de matemática em suas atividades diárias.

## 🎯 Funcionalidades

### Módulos Principais:
- 📚 **Estudos**: Cronogramas, acompanhamento de progresso e técnicas de estudo
- 🐍 **Python Tutor**: Tutoria especializada em Python para iniciantes
- 💼 **Freelances**: Gerenciamento de projetos freelancer e orçamentos
- 🧮 **Matemática**: Resolução de equações, gráficos e cálculos
- 📋 **Tarefas Pessoais**: Organização e gestão de tarefas
- 💰 **Financeiro**: Controle financeiro pessoal

### Chat Inteligente:
- Conversação natural powered by OpenAI
- Respostas contextualizadas para cada área
- Interface web amigável com Streamlit

## 🚀 Como Executar

### 1. Instalar Dependências
```bash
pip install -r requirements.txt
```

### 2. Configurar API OpenAI
Copie o arquivo `.env.example` para `.env` e configure sua chave:
```bash
copy .env.example .env
```

Edite o arquivo `.env` e adicione sua chave OpenAI:
```
OPENAI_API_KEY=sua_chave_aqui
```

### 3. Executar a Aplicação
```bash
streamlit run main.py
```

## 📁 Estrutura do Projeto

```
buster/
├── main.py                    # Ponto de entrada
├── requirements.txt           # Dependências
├── .env.example              # Exemplo de configuração
├── core/                     # Funcionalidades principais
│   ├── agente_principal.py   # Classe principal do Buster
│   └── openai_integration.py # Integração com OpenAI
├── modules/                  # Módulos funcionais
│   ├── estudos/
│   ├── python_tutor/
│   ├── freelas/
│   ├── matematica/
│   ├── tarefas_pessoais/
│   └── financeiro/
├── interface/                # Interface web
│   └── interface_streamlit.py
└── database/                 # Gerenciamento de dados
    └── database_manager.py
```

## 🛠️ Tecnologias Utilizadas

- **Python 3.11+**: Linguagem principal
- **Streamlit**: Interface web interativa
- **OpenAI API**: Inteligência artificial conversacional
- **SQLite**: Banco de dados local
- **Pandas**: Manipulação de dados
- **Plotly**: Visualizações interativas

## 📋 Requisitos

- Python 3.11 ou superior
- Chave da API OpenAI
- Conexão com internet

## 🔧 Status do Desenvolvimento

### ✅ Implementado:
- ✅ Estrutura básica do projeto
- ✅ Sistema de chat com OpenAI
- ✅ Interface web com Streamlit
- ✅ Banco de dados SQLite
- ✅ Arquitetura modular

### 🚧 Em Desenvolvimento:
- 🚧 Funcionalidades específicas de cada módulo
- 🚧 Persistência de dados
- 🚧 Gráficos e visualizações
- 🚧 Sistema de usuários

### 📋 Próximas Funcionalidades:
- 📱 Integração com WhatsApp
- 📊 Dashboard analítico
- 🔐 Sistema de autenticação
- 📤 Export de relatórios

## 👨‍💻 Como Contribuir

1. Clone o repositório
2. Crie uma branch para sua feature
3. Implemente suas melhorias
4. Teste thoroughly
5. Faça um pull request

## 📞 Suporte

Para dúvidas ou sugestões sobre o **Buster**, utilize o chat integrado ou contribua com o projeto!

## 📄 Licença

Este projeto é desenvolvido para fins educacionais e de pesquisa.

---

**Buster** - Seu assistente inteligente para estudos e organização! 🎓🚀
