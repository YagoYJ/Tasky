This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Package Manager

Para instalação de bibliotecas, vamos utilizar o `pnpm`. Para instalar, basta rodar o comando ```cmd npm i -g pnpm``` no terminal.

## Eslint

O projeto está seguindo as configurações do vídeo da [Rocketseat](https://youtu.be/cbSHUVSUFgY?si=hMa7rV-B4ZS05YhV)

## Components

O projeto utiliza os componentes do [Shadcn/ui](https://ui.shadcn.com/), todo componente instalado pela biblioteca deve ficar em `src/app/components/ui`, componentes criados manualmente devem ficar em `src/app/components`.

## Paleta

As cores utilizadas devem respeitar as cores padrões do [Tailwind](https://tailwindcss.com/), bem como espaçamentos, tamanhos de fontes, etc.

## Payloads e Responses

Todas as requests devem utilizar os schemas feitos com [Zod](https://zod.dev/). Todos os schemas, tipagem de payloads e tipagem de responses vão ficar na pasta `src/contracts`