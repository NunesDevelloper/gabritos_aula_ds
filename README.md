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
| 08/6 | Conceitos(Rest Api, framework, etc)                    | Samuel    |
| 10/6 | Apresentar sobre o Fastapi (docs)                       | Pedro.D    |
| 12/6 | CRUD(Arquitura do projeto, modelagem no Workbench, etc) | Cris       |
| 15/6 | Conexção Python+Banco                                 | Pedro.S    |
| 17/6 | Services e Schema                                       | Lucas      |
| 19/6 | JWT, HASH                                               | Fernando   |
| 22/6 | Endpoints, CORS                                         | Coelho     |
| 24/6 | Docker e Deploy                                         | Nunes      |
