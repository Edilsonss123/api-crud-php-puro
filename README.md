# CRUD de Pessoas (People) - PHP Puro

## Sobre o Projeto
Este é um projeto de CRUD para a entidade `People`, desenvolvido em **PHP puro**, sem o uso de frameworks. O sistema permite operações básicas como **criação, leitura, atualização e exclusão** de registros de pessoas.

> 🚀 **Desenvolvido durante o final de semana de Carnaval, sem internet😓!**

## Funcionalidades
✅ Listar todas as pessoas cadastradas  
✅ Buscar uma pessoa pelo ID  
✅ Criar uma nova pessoa  
✅ Atualizar uma pessoa existente  
✅ Deletar uma pessoa do banco de dados  

## Rotas da API

### 1️⃣ Listar Todas as Pessoas
- **Método:** `GET`
- **Rota:** `/peoples`
- **Descrição:** Retorna uma lista de todas as pessoas cadastradas.

### 2️⃣ Buscar Pessoa por ID
- **Método:** `GET`
- **Rota:** `/people`
- **Parâmetro:** `id` (via query param)
- **Descrição:** Retorna os detalhes de uma pessoa específica com base no `id` fornecido.

### 3️⃣ Criar uma Nova Pessoa
- **Método:** `POST`
- **Rota:** `/people`
- **Descrição:** Cria um novo registro de pessoa.
- **Body (JSON):**

### 4️⃣ Atualizar uma Pessoa
- **Método:** `PUT`
- **Rota:** `/people`
- **Descrição:** Atualiza os dados de uma pessoa existente.
- **Body (JSON):**

### 5️⃣ Deletar uma Pessoa
- **Método:** `DELETE`
- **Rota:** `/people`
- **Parâmetro:** `id` (via query param)
- **Descrição:** Remove uma pessoa do banco de dados.


## Configuração e Execução
1. Clone o repositório
   ```sh
   git clone https://github.com/Edilsonss123/api-crud-php-puro.git seu-repositorio
   ```
2. Acesse o diretório do projeto
   ```sh
   cd seu-repositorio
   ```
4. Inicie o container com o pgp
   ```sh
   docker-compose up -d
   ```
   
5. Inicie um servidor embutido do PHP
   ```sh
   php -S localhost:8000 -t index.php
   ```
6. Acesse no navegador: [http://localhost:8023/peoples](http://localhost:8023/peoples)

## Tecnologias Utilizadas
- PHP Puro
- SQLite (ou outro banco de dados à escolha)
- JSON para comunicação entre API e cliente

## Melhorias Futuras
- 🔹 Projeto será utilizado como ponto de partida para treinamento de teste de software 

