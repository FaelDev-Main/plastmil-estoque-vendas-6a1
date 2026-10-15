# Plastmil - Controle de Estoque e Vendas

Este projeto utiliza Node.js, Vite e pnpm. Siga as instruções abaixo para configurar e executar a aplicação localmente.

## Pré-requisitos

Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas em sua máquina:
- Node.js (versão 18 ou superior recomendada)
- pnpm (gerenciador de pacotes)

Caso não tenha o pnpm instalado, você pode instalá-lo globalmente executando o seguinte comando no seu terminal:

npm install -g pnpm

## Configuração e Instalação

1. Extraia os arquivos do projeto em uma pasta de sua preferência.
2. Abra o terminal e navegue até o diretório raiz do projeto.
3. Instale todas as dependências necessárias executando:

pnpm install

## Configuração de Ambiente

O projeto utiliza variáveis de ambiente para configurações, incluindo a conexão com o banco de dados via Drizzle ORM.

1. Na raiz do projeto, localize o arquivo `.env.example`.
2. Faça uma cópia deste arquivo e renomeie a cópia para `.env`.
3. Abra o arquivo `.env` em um editor de texto e preencha as variáveis com as informações do seu ambiente local.

## Execução

Após instalar as dependências e configurar o arquivo `.env`, inicie o servidor de desenvolvimento com o comando:

pnpm run dev

O terminal exibirá o endereço local onde a aplicação está rodando (geralmente http://localhost:5173 ou http://localhost:3000). Abra este endereço no seu navegador para acessar o sistema.
