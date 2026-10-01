# Add packages
This repo uses `uv` not pip
So instead of pip install fastapi please use `uv add fastapi` for example.
This adds dependencies to the pyproject.toml

When you pull run:
`uv sync`


# API Spec
## /account/create
[POST]
## /account/login
[POST]
## /account/logout
[POST]
## /account/{account_id}
[GET, PUT, DELETE]
## /items/{item_id}
[GET, PUT, POST, DELTE]
## 