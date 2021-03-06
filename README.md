# AC 05 Tech Web

Integrantes

Anderson da Silva Machado RA: 1902142<br>
Bruno Santos de Assunção RA.: 1902440<br>
Matheus Marques Silva RA: 1801198<br>
Gledson da Silva RA: 1200279<br>
Priscila Da Dalt RA: 1901843<br>


# Inicialização

Copie esse repositório para usar como base de projetos Flask

No Git Bash podemos executar o comando:

```
git clone https://github.com/fabiogoro/flask-base
```

Isso irá copiar o repositório na pasta flask-base.

Depois entramos na pasta do projeto:

```
cd flask-base
```

Então criamos o ambiente virtual com os pacotes necessário para esse projeto:

```
virtualenv venv
source venv/Scripts/activate
pip install -r requirements.txt
```

Depois precisamos realizar a criação do banco de dados:

```
python cria_bd.py
```

A partir daí podemos executar e visualizar o projeto.
Para executar:

```
python controllers.py
```


## Estrutura

Esse projeto contém a seguinte estrutura:

### aplicacao.py

Inicializa e configura a aplicação Flask.

### controllers.py

Contém os controllers e rotas da aplicação.

### static/

Contém arquivos estáticos, como css.

### templates/

Contém as views da aplicação. O arquivo base.html é usado como arquivo principal, herdado por todos os templates.

### banco.py

Contém as funções necessárias para conectar no banco.

### cria_bd.py

Script para criação do banco.

### esquema.sql

Contém a estrutura do banco de dados. Para alterar o banco, altere esse arquivo.
