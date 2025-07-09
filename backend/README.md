# ⚙️ Backend – API FastAPI do BuildPrice

Este módulo fornece a API REST do BuildPrice, responsável por autenticação de usuários, gestão de orçamentos e integração com o banco de dados PostgreSQL.

---

## 🚀 Tecnologias Utilizadas

- Python 3.11+
- FastAPI
- Uvicorn (servidor ASGI)
- SQLAlchemy
- PostgreSQL (via Supabase)
- dotenv

---

## 📦 Como Rodar o Backend Localmente

### 1. Criar e ativar o ambiente virtual:

```bash
cd backend
python -m venv venv
venv\Scripts\activate
```

### 2. Instalar dependências:

```bash
pip install -r requirements.txt
```

### 3. Rodar a API:

```bash
uvicorn app.main:app --reload
```

API disponível em: http://127.0.0.1:8000  
Documentação automática: `/docs` (Swagger)

---

## 🛢️ Banco de Dados

- O banco é hospedado no Supabase
- Você deve configurar as variáveis de ambiente em um arquivo `.env`:
  
```env
DATABASE_URL=postgresql://usuario:senha@host:porta/dbname
```

---

## 🧪 Testes

Execute os testes com:

```bash
pytest
```

---

## 📂 Estrutura Recomendada

```
backend/
├── app/
│   ├── main.py
│   ├── routes/
│   ├── models/
│   └── services/
├── venv/
└── requirements.txt
```