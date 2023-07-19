# How to publish

Criando o ambiente virtual, ativando e instalado as dependências

```bash
python3 -m venv .venv
# source .venv/Scripts/activate
# A alternativa é usar uma outra bash:
bash --init-file .venv/Scripts/activate
cp .venv/Scripts/python.exe .venv/Scripts/python3.exe
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
python3 -m pip list | grep datascience
```

Criando o book

```bash
jupyter-book build --all .
```

```bash
```

```bash
```

Desativando o ambiente virtual

```
# deactivate
exit # ou [CTRL+D]
```

