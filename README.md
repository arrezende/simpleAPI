
# simpleAPI

Este projeto é uma API RESTful construída com Laravel.

##  Tecnologias Utilizadas
- PHP 8.x
- Laravel
- SQLITE


##  Instalação e Configuração

### 1. Clonar o repositório
```bash
git clone https://github.com/arrezende/simpleAPI.git
cd simpleAPI
```

### 2. Instalar dependências
```bash
composer install
```

### 3. Configurar o ambiente
Copie o arquivo `.env.example` para `.env` e edite as configurações do banco de dados, se necessário:
```bash
cp .env.example .env
```

### 4. Gerar a chave da aplicação
```bash
artisan key:generate
```

### 5. Rodar as migrações do banco de dados
```bash
artisan migrate
```

##  Rotas da API

| Método | Rota             | Descrição                         |
|--------|-----------------|---------------------------------|
| POST   | `/users`        | Criar um novo usuário          |
| GET    | `/users`        | Listar todos os usuários       |
| GET    | `/users/{id}`   | Buscar um usuário por ID       |
| PUT    | `/users/{id}`   | Atualizar um usuário existente |
| DELETE | `/users/{id}`   | Deletar um usuário             |
