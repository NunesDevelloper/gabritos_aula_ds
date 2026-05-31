# Notas:

## O indicado seria que cada crie uma branche para cada parte de aula caso nesside do código do projeto. Pois assim teriam o Gabarito e garantia que todas partes da aula sejam compativeis uma com a outra.

## Arquitetura:

projeto-fastapi/
├── .venv/
├── alembic/
├── docs/
├── src/
│   ├── database/
│   │   ├── _init_.py
│   │   ├── base.py
│   │   ├── engine.py
│   │   └── session.py
│   ├── models/
│   │   ├── _init_.py
│   │   └── user_model.py
│   ├── routers/
│   │   ├── _init_.py
│   │   └── user_routes.py
│   ├── schemas/
│   │   ├── _init_.py
│   │   └── user_schemas.py
│   ├── services/
│   │   ├── _init_.py
│   │   └── user_services.py
│   ├── _init_.py
│   └── main.py
├── .env
├── .env.example
├── .gitignore
├── alembic.ini
└── requirements.txt
