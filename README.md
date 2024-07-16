
# Gerenciamento de Ingredientes e Receitas

Este projeto é uma aplicação web desenvolvida para gerenciar ingredientes e receitas. Ele permite que os usuários cadastrem novos ingredientes, criem receitas associando ingredientes e visualizem as listas de ingredientes e receitas existentes.

## Funcionalidades

- Cadastro e edição de ingredientes
- Cadastro e edição de receitas
- Associação de ingredientes a receitas
- Visualização de listas de ingredientes e receitas

## Tecnologias Utilizadas

- **Frontend**:
  - React
  - HTML
  - Bootstrap
  - Fetch API

- **Backend**:
  - Spring Boot
  - Spring Data JPA
  - MySQL

## Configuração

### Backend (Spring Boot)

1. Clone o repositório:

   ```bash
   git clone https://github.com/marlonszpak/desafio-sistemairis.git
   ```

2. Abra o projeto backend no IntelliJ IDEA ou outra IDE de sua preferência.

3. Configure as credenciais do banco de dados MySQL em `src/main/resources/application.properties`:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/desafio
   spring.datasource.username=seu-usuario
   spring.datasource.password=sua-senha
   ```

4. Execute o aplicativo Spring Boot.

### Frontend (React)

1. Navegue até o diretório do frontend:

   ```bash
   cd nome-do-repositorio
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:

   ```bash
   npm start
   ```

4. O frontend estará acessível em `http://localhost:3000`.

## Uso

- Acesse a aplicação pelo navegador e utilize as funcionalidades de cadastro de ingredientes e receitas conforme necessário.
