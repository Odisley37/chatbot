# 🤖 Chat PyGPT

Uma aplicação de chatbot baseada em GPT que utiliza **LangChain** para realizar consultas em arquivos PDF. Crie bancos de dados a partir de seus documentos e obtenha respostas interativas e bem formatadas em português.

---

## 🛠️ Tecnologias Utilizadas

- **[Streamlit](https://streamlit.io/)** - Para criar a interface interativa do aplicativo.
- **[LangChain](https://langchain.com/)** - Para processamento de linguagem natural e integração com LLMs.
- **[Chroma](https://www.trychroma.com/)** - Armazenamento e recuperação de vetores para consultas eficientes.
- **[OpenAI GPT](https://openai.com/)** - Modelos de linguagem para responder perguntas com base no conteúdo dos documentos.
- **[Python-Decouple](https://pypi.org/project/python-decouple/)** - Gerenciamento de variáveis de ambiente.
- **SQLite** - Para persistir dados vetoriais localmente.

---

## 🚀 Funcionalidades

- **📂 Upload de arquivos PDF**: Faça o upload de um ou mais arquivos PDF.
- **🔍 Consulta Inteligente**: Crie um banco de dados vetorial e consulte informações diretamente nos documentos.
- **🤝 Modelos GPT**: Escolha entre modelos como `gpt-3.5-turbo` e `gpt-4` para obter respostas precisas.
- **📊 Respostas Elaboradas**: As respostas são fornecidas em Markdown e formatadas para facilitar a leitura e interação.

---

## 📋 Como Configurar

### Pré-requisitos

- Python 3.8 ou superior.
- Uma chave de API do OpenAI.

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Odisley37/chatbot.git
   cd chat-pygpt
### 🎮 Como Usar
1. Inicie a aplicação Streamlit:
```streamlit run main.py```
2. Abra o navegador no endereço exibido no terminal (geralmente http://localhost:8501).

3. Upload de PDFs:

4. Faça upload de arquivos PDF usando a barra lateral.
Os documentos serão processados e armazenados em um banco vetorial.
Faça Perguntas:

5. Utilize o campo de entrada do chatbot para fazer perguntas relacionadas ao conteúdo dos PDFs.
O modelo GPT processará a pergunta e fornecerá respostas detalhadas.
### 🧩 Demonstração das Funções
Barra Lateral:

📂 Upload de arquivos PDF.
🎛️ Escolha do modelo GPT.
📑 Informações sobre a aplicação.
Chat Interativo:

Insira perguntas no campo de entrada.
Respostas são exibidas com formatação amigável.

### 📦 Estrutura do Projeto
chat-pygpt/
├── db/                       # Diretório para o armazenamento vetorial
├── main.py                   # Arquivo principal da aplicação Streamlit
├── requirements.txt          # Dependências do projeto
├── .env                      # Variáveis de ambiente (não incluído no repositório)
├── README.md                 # Documentação do projeto

### 📝 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

### 📬 Contato
Autor: Odisley
E-mail: odisleyribeirosilva@gmail.com
GitHub: Odisley37


````Este README inclui ícones para seções importantes, como tecnologias, funcionalidades, e instruções de uso. Ajuste os links e informações pessoais de acordo com o contexto do seu projeto.````
### Odisley Silva 