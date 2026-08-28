# Portfólio — João Assunção

Portfólio pessoal de desenvolvimento web, construído em público como parte de uma trilha de estudos de ~8–9 meses rumo a uma vaga de estágio/júnior em frontend no mercado brasileiro.

Este repositório é ao mesmo tempo **o produto final** (o site que vai no currículo e no LinkedIn) e **o registro do aprendizado**: ele evolui junto com a trilha, de uma página estática em HTML/CSS até uma aplicação React + TypeScript testada, acessível e publicada.

## Objetivo

Ter, ao final da trilha, um portfólio que passe no crivo de recrutadores e tech leads brasileiros:

- **React + TypeScript**, a combinação que mais aparece nas vagas júnior de empresas como Nubank, Globo, PagBank, Mercado Livre, iFood, Stone e C6 Bank.
- **Deploy ao vivo** e instantâneo (sem backend hibernando), na Vercel.
- **2–3 projetos autorais** em destaque — nada de clone de tutorial ou to-do list como carro-chefe.
- **Responsivo, acessível e rápido**, com README claro, commits limpos e código organizado.

A habilidade fullstack é provada em um **projeto separado** (React + TS no frontend, Node/Express + PostgreSQL no backend), linkado a partir daqui — o site de portfólio em si é deliberadamente frontend puro, para carregar rápido e mostrar primeiro o que é avaliado primeiro.

## Status atual

| | |
|---|---|
| **Fase da trilha** | Fase 0 — ambiente e mentalidade |
| **Versão do portfólio** | ainda não publicada (v1 nasce ao fim da Fase 2) |
| **Deploy** | — |

Roteiro completo de estudos, fases, mini-desafios e critérios de aceitação: [TRILHA.md](TRILHA.md).

## Roadmap de versões

| Versão | Quando | O que muda | Hospedagem |
|---|---|---|---|
| **v1** | após a Fase 2 (CSS) | página estática em HTML/CSS semântico e responsivo, já linkável no currículo | GitHub Pages |
| **v2** | após a Fase 6 (React) | reescrita em componentes React, com dados de projetos e integração com a API do GitHub | Vercel |
| **v2.5** | após a Fase 7 (TypeScript) | migração para TS — props, estado e respostas de API tipadas, sem `any` implícito | Vercel |
| **v3** | após a Fase 9 (testes/deploy) | versão final: testes (Jest + Testing Library), auditoria de acessibilidade e performance, CI no GitHub Actions, projeto fullstack de vitrine linkado | Vercel |

## Stack

**Atual:** HTML5 semântico, CSS3.

**Planejada:** JavaScript (ES6+) · Vite · React · TypeScript · React Router · Jest + Testing Library · ESLint + Prettier · GitHub Actions · Vercel.

## Estrutura do repositório

```
.
├── README.md    # este arquivo
└── TRILHA.md    # trilha de aprendizado e plano de portfólio
```

A estrutura de código será documentada aqui conforme o projeto ganhar arquivos.

## Como rodar localmente

Ainda não há aplicação para executar. As instruções entram junto com a v1 (abrir o HTML no navegador) e são atualizadas na v2, quando o projeto passa a ter dependências e scripts de build.

## Convenções

- **Commits** com mensagens descritivas em português, no imperativo, explicando o *quê* e o *porquê* — nada de "update".
- **Acessibilidade** como requisito, não como polimento: HTML semântico, texto alternativo em imagens, rótulos em formulários, foco visível e navegação completa por teclado.
- **Mobile-first**: layouts pensados a partir de 320px.

## Licença

Código sob licença MIT. Conteúdo textual, imagens e identidade visual são de uso pessoal e não devem ser reaproveitados como portfólio próprio.
