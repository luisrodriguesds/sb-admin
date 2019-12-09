# SB-Admin - Sistema Base de Administração
Aplicação feita com Adonisjs, front e backend, com toda a parte de criação, autenticação e validação de usuários.

## Setup

Instale o adonis com

```bash
npm i -g @adonisjs/cli
```

Clone este espositório com 

```bash
git clone https://github.com/luisrodriguesds/sb-admin.git
```

Dentro da pasta digite

```bash
npm i
```

Depois copie o .env.exemple com o nome de .env e depois migre o banco com 

```bash
adonis migration:run
```

Por fim, 

```bash
adonis serve --dev
```

Mais informações em https://adonisjs.com/docs/4.1/installation