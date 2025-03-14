# 📝 To-Do List - Aplicação Flask com Docker  

Um simples sistema de **Lista de Tarefas** desenvolvido com **Flask** e containerizado com **Docker**.  

---

## 🚀 Tecnologias Utilizadas  
- 🐍 **Python** (Flask)  
- 🗄 **SQLite** (Banco de Dados)  
- 🐳 **Docker** (Containerização)  

---

## 📦 Como Executar o Projeto  

### 🔧 **1. Clonar o repositório**  
Primeiro, faça o clone deste repositório:  
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
'''bash

### 🏗 2. Criar o ambiente virtual (Opcional para rodar localmente)

Se quiser rodar localmente sem Docker, crie um ambiente virtual:

python -m venv .venv
source .venv/Scripts/activate  # Windows (Git Bash)
source .venv/bin/activate  # Linux/macOS

### 📥 3. Instalar as dependências (Opcional para rodar localmente)

Se estiver rodando sem Docker, instale as dependências:

pip install -r requirements.txt

### 🏗 4. Criar o banco de dados

Antes de rodar a aplicação, inicialize o banco de dados executando:

python init_db.py

### 🐳 5. Construir e rodar a aplicação com Docker

Agora, crie a imagem e inicie o container:

docker build -t flask-app .
docker run -p 5000:5000 flask-app

### 📌 6. Acessar a aplicação

Abra seu navegador e acesse:
http://127.0.0.1:5000/

### 🚀 Executar com Docker Compose (Opcional)

Caso queira rodar com Docker Compose, execute:

docker compose up -d --build

Para parar a aplicação com Docker Compose:

docker compose down

### 🛠 Funcionalidades

✅ Adicionar tarefas
✅ Listar tarefas
✅ Marcar tarefas como concluídas
✅ Excluir tarefas
🎯 Estrutura do Projeto

📂 seu-projeto/
│-- 📄 app.py              # Código principal da aplicação Flask  
│-- 📄 init_db.py          # Script para inicializar o banco de dados  
│-- 📄 requirements.txt    # Dependências do projeto  
│-- 📄 Dockerfile          # Configuração para criação do container  
│-- 📄 docker-compose.yml  # (Opcional) Arquivo para orquestração do Docker  
│-- 📂 templates/          # Arquivos HTML da interface  
│-- 📂 .venv/              # (Opcional) Ambiente virtual Python  

### 🛑 Como Parar a Aplicação

Se rodou o container com docker run, pare o container com:

docker ps  # Para listar os containers em execução
docker stop <CONTAINER_ID>  # Para parar um container específico

Se usou Docker Compose, pare a aplicação com:

docker compose down

🛡 Licença

Este projeto é de código aberto e pode ser utilizado para estudos e melhorias. 🚀

###📌 Feito com ❤️ por Otávio L. de Giacometti


Agora **é só copiar e colar**! 🚀🔥 
