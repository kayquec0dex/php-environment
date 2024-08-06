# Projeto PHP em Docker

Este repositório contém a configuração para criar um ambiente de desenvolvimento PHP utilizando Docker.

## Estrutura do Projeto

- `Dockerfile`: Arquivo para construir a imagem Docker com PHP e dependências.
- `docker-compose.yml`: Arquivo para configurar e iniciar os serviços Docker.
- `src/`: Diretório para armazenar o código fonte PHP.

## Requisitos

- Docker
- Docker Compose

## Configuração

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/kayquec0dex/php-environment.git
   cd php-environment
   ```

2. **Construa e inicie os conteiners**

   ```bash
   docker-compose up --build
   ```

3. **Acesse o ambiente:**
   O ambiente estará acessível em `http://localhost:8080` no seu navegador.

4. Encerramento
   Para parar e remover os containers, use:
   ```bash
   docker-compose down
   ```

## Contribuição

Sinta-se à vontade para abrir issues ou pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
