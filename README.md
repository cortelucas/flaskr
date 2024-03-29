# Flaskr

## Windows
- Clone ou baixe o projeto:
  - ```git clone https://github.com/cortelucas/flaskr.git```

- Crie um novo ambiente virtual:  
  - ```python -m venv venv```
- Abra o PowerShell em Modo Administrador e execute:
  - ```Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned```
- No PowerShell ative o ambiente virtual: 
  - ```venv\Scripts\activate.ps1```
- Instale as dependências:
  - ```pip3 install -r requirements.txt```
- Set as variáveis de ambiente: 
  - ```$Env:FLASK_APP="flaskr"```
  - ```$Env:FLASK_ENV="development"```
- Execute a aplicação:
  - ```flask run```


## Linux

- Clone ou baixe o projeto:
  - ```git clone https://github.com/cortelucas/flaskr.git```

- Crie um novo ambiente virtual:  
  - ```python -m venv venv```
- No PowerShell ative o ambiente virtual: 
  - ```source venv\bin\activate```
- Instale as dependências:
  - ```pip3 install -r requirements.txt```
- Set as variáveis de ambiente: 
  - ```export FLASK_APP=flaskr```
  - ```export FLASK_ENV=development```
- Execute a aplicação:
  - ```flask run```