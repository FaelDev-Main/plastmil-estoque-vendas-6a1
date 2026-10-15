# Plastmil - Controle de Estoque e Vendas

Este projeto é um sistema web (Single Page Application) desenvolvido para o controle simplificado de estoque, registro de vendas e gestão de pagamentos da empresa Plastmil.

Abaixo estão as instruções detalhadas para configurar e executar a aplicação no seu ambiente local.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas no seu sistema operacional:
- Node.js (versão 18 ou superior recomendada)
- pnpm (gerenciador de pacotes configurado para este projeto)

Caso não tenha o pnpm instalado, você pode instalá-lo globalmente no seu computador através do npm executando o seguinte comando no terminal:
npm install -g pnpm

## Passo a Passo para Instalação e Execução

### 1. Obter os arquivos do projeto
Se você recebeu o projeto em um arquivo compactado (como .zip), extraia todo o conteúdo para uma pasta de sua preferência. Se estiver utilizando o Git, clone o repositório para a sua máquina.

### 2. Acessar a pasta do projeto
Abra o seu terminal ou prompt de comando e navegue até a pasta raiz onde os arquivos foram extraídos. 
Exemplo:
cd caminho/para/a/pasta/do/projeto

### 3. Instalar as dependências
Com o terminal aberto na raiz do projeto, execute o comando abaixo. Ele lerá os arquivos de configuração e baixará todos os pacotes necessários para o sistema funcionar.
pnpm install

### 4. Configurar as variáveis de ambiente
Na pasta raiz, você encontrará um arquivo chamado `.env.example`. 
- Faça uma cópia deste arquivo no mesmo diretório.
- Renomeie essa nova cópia para `.env` (sem nenhum nome antes do ponto).
- Abra este arquivo `.env` em um editor de texto e preencha os dados necessários, como configurações locais de banco de dados (Drizzle) caso aplicável.

### 5. Iniciar o servidor de desenvolvimento
Após a instalação das dependências e a configuração do ambiente, inicie a aplicação executando o comando:
pnpm run dev

### 6. Acessar a aplicação
Após executar o comando acima, o terminal exibirá um endereço local (normalmente http://localhost:5173 ou http://localhost:3000). Abra o seu navegador de internet, digite esse endereço e você terá acesso ao sistema.