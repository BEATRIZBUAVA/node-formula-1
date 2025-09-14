# Minimal API Fórmula 1

API minimalista de Fórmula 1 usando Node.js, TypeScript e Fastify.

## Como rodar

### Desenvolvimento (hot reload)

```bash
npm run dev
```

### Produção (compilado para JS)

```bash
npm run build
npm start
```

## Rotas disponíveis

- `GET /` — Mensagem de status da API
- `GET /teams` — Lista todas as equipes
- `GET /drivers` — Lista todos os pilotos
- `GET /drivers/:id` — Detalhe de um piloto por ID

## Configuração de porta

A porta padrão é 3333. Você pode alterar criando um arquivo `.env`:

```
PORT=3333
```

## Requisitos

- Node.js 18+
- npm

---

Inspirado no projeto [node-formula-1](https://github.com/digitalinnovationone/node-formula-1)
