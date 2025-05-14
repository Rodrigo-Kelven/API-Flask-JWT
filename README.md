# API Flask com Autenticação JWT
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) 
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) 
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-%23C72C41.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white)


Esta é uma API simples construída com Flask que implementa autenticação usando JSON Web Tokens (JWT). A API permite o registro de usuários, login e acesso a rotas protegidas.

## Funcionalidades.

- Registro de novos usuários
- Login de usuários existentes
- Geração de tokens JWT para autenticação
- Acesso a rotas protegidas com autenticação JWT

## Tecnologias Utilizadas.

- Python 3.x
- Flask
- Flask-SQLAlchemy
- Flask-Migrate
- PyJWT
- SQLite (banco de dados)

## Pré-requisitos.

Antes de começar, você precisará ter o Python e o pip instalados em sua máquina. Você pode baixar o Python [aqui](https://www.python.org/downloads/).

## Instalação:

### 1. Clone o repositório:

   ```bash
   git clone https://github.com/Rodrigo-Kelven/API-Flask-JWT.git
   cd API-Flask-JWT
   ```
### 2. Instale as dependencias:
   ```bash
   pip install -r requirements.txt
   ```
### 3. Rode a API:
   ```bash
   python app.py --reload
   ```

# Usando Insomnia
## Criando uma coleção para guardar as url's.
![Minha Imagem](images/Parte1.png)

## Cadastrando as url's.
![Minha Imagem](images/Parte2.png)

## Testando a primeira rota.
![Minha Imagem](images/Parte3.png)

## Criando usuário.
![Minha Imagem](images/Parte4.png)

## Pegando token de login.
![Minha Imagem](images/Parte5.png)

## Passando o token no lugar correto.
![Minha Imagem](images/Parte6.png)

## Acessando a rota protegida, so é possivel acessar passando o token de login.
![Minha Imagem](images/Parte7.png)

## Autores
- [@Rodrigo_Kelven](https://github.com/Rodrigo-Kelven)

## Colaboradores
- [@Tiago-Dev0708](https://github.com/Tiago-Dev0708)

