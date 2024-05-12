# Rede Social Backend
Este é o Back-End do projeto da Rede Social feito com [FastAPI](https://fastapi.tiangolo.com/)

## Como Rodar
_Para prosseguir, é necessário que tenha instalado na máquina Python (versão 3.10+)_

Crie um virtual env:
```console
python3 -m venv .venv 
```

Ative o virtual env
```console
source .venv/bin/activate
```

Instale as dependências
```console
pip install -r requirements.txt
```

Rode o servidor no modo de desenvolvimento
```console
fastapi dev app/main.py
```

Pronto! Agora você já pode testar o servidor
acessando http://127.0.0.1:8000/

O FastAPI também tem um recurso de documentação 
criada automaticamente, para visualizar basta acessar 
http://127.0.0.1:8000/docs ou http://127.0.0.1:8000/redoc