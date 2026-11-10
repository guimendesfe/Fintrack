# FinTrack

Sistema de Controle Financeiro Full Stack.

## Objetivo

Aplicação web para gerenciamento de receitas,
despesas e visualização de indicadores financeiros.

## Tecnologias

- React + TypeScript
- Node.js + Express
- PostgreSQL + Prisma
- Docker

## Status

Em desenvolvimento.

## Funcionalidades do MVP

- Autenticação de usuários
- Gerenciamento de transações
- Categorias financeiras
- Filtros
- Dashboard com gráficos

## Ambiente de desenvolvimento

### Pré-requisitos

- Git
- Docker Desktop com Docker Compose

### Executando o PostgreSQL

1. Clone o repositório.
2. Copie `.env.example` para `.env`.
3. Configure uma senha forte no `.env`.
4. Execute:

docker compose up -d db

### Verificar o banco

docker compose ps

### Parar o ambiente

docker compose down

Os dados são armazenados em um volume Docker,
permitindo sua persistência entre reinicializações.