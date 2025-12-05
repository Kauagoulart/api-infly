📊 API Infly – Sistema de Gestão Escolar

A API Infly foi desenvolvida para gerenciar negociações, contas, calendários, leads e matrículas dentro de um sistema escolar.
Ela fornece endpoints completos para consulta, análise e controle, permitindo extrair métricas como:

Taxa de conversão

Inadimplência

Origem dos leads

Distribuição de matrículas

Controle financeiro e acadêmico

O módulo é ideal para integração com dashboards (ex.: Power BI) e com qualquer frontend web ou mobile.

🚀 Tecnologias Utilizadas

Python 3.10+

FastAPI – Framework moderno e de alta performance

Uvicorn – Servidor ASGI

SQLAlchemy – ORM para gerenciamento do banco de dados

PostgreSQL – Banco de dados relacional principal

Pydantic – Modelos para validação e serialização

Argon2 – Hash seguro para senhas

PyJWT (python-jose) – Autenticação baseada em JWT

CORS Middleware – Permite acesso seguro por frontends externos

📦 Instalação
1️⃣ Clone o repositório
git clone https://github.com/seu-user/api-infly.git
cd api-infly

📜 Instalação das Dependências
2️⃣ Crie e ative um ambiente virtual
🔹 Windows
python -m venv venv
venv\Scripts\activate

🔹 Linux / macOS
python3 -m venv venv
source venv/bin/activate

3️⃣ Instale os pacotes
pip install -r requirements.txt

▶️ Como Executar o Servidor

Com o ambiente virtual ativado e dentro da pasta do projeto:

🔹 Windows / Linux / macOS
uvicorn api_infly.main:app --reload

Ajuste o path conforme a estrutura do seu projeto (api-infly, api_infly, etc.).

✨ Principais Funcionalidades

📚 Gestão de matrículas

💬 Gerenciamento de leads

📅 Calendário escolar

🧾 Gestão de contas e negociações

📊 Geração de métricas e análises

🔐 Autenticação JWT

🛡️ Hash seguro de senhas com Argon2

🗄️ Integração com PostgreSQL via SQLAlchemy

🌐 API documentada via Swagger e ReDoc

👥 Integrantes da Equipe

Kauã Goulart
Iuri Colomé
Victor Rannow

(Preencha conforme seu projeto.)
