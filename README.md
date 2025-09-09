- Crie o arquivo ``.env`` copiando o ``.env.example``. no terminal, execute:

```bash 
cp .env.example .env
```

Edite o ``.env`` configurando com base o seu banco de dados

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=seuBancoDeDados
DB_USERNAME=seuNomeDeUsuario
DB_PASSWORD=suaSenha
```

- Gere a chave da aplicação no ``.env`` para criptografar dados sensíveis:

```bash
php artisan key:generate
```