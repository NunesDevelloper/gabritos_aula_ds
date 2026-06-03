# Notas:

## O indicado seria que cada cria	 uma branche para cada parte de aula caso nesside do código do projeto. Pois assim teriam o Gabarito e garantia que todas partes da aula sejam compativeis uma com a outra.

## Arquitetura:

```
projeto-fastapi/
├── .venv/
├── alembic/
├── docs/
├── src/
│   ├── database/
│   │   ├── __init__.py
│   │   ├── base.py
│   │   ├── engine.py
│   │   └── session.py
│   ├── models/
│   │   ├── __init__.py
│   │   └── user_model.py
│   ├── routers/
│   │   ├── __init__.py
│   │   └── user_routes.py
│   ├── schemas/
│   │   ├── __init__.py
│   │   └── user_schemas.py
│   ├── services/
│   │   ├── __init__.py
│   │   └── user_services.py
│   ├── __init__.py
│   └── main.py
├── .env
├── .env.example
├── .gitignore
├── alembic.ini
└── requirements.txt
```

# Dias da aulas:

| DIA  | CONTEUDO                                                | REPONSAVEL |
| ---- | ------------------------------------------------------- | ---------- |
| 24/7 | Conceitos(Rest Api, framework, etc)                    | Samuel    |
| 27/7 | Apresentar sobre o Fastapi (docs)                       | Pedro.D    |
| 29/7 | CRUD(Arquitura do projeto, modelagem no Workbench, etc) | Cris       |
| 31/7 | Conexção Python+Banco                                 | Pedro.S    |
| 03/8 | Services e Schema                                       | Lucas      |
| 05/8 | JWT, HASH                                               | Fernando   |
| 07/8 | Endpoints, CORS                                         | Coelho     |
| 10/8 | Docker e Deploy                                         | Nunes      |
