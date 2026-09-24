# PRD — Driverthu

## Problem Statement (original)
Altere o nome do aplicativo para "Driverthu" em todo o projeto. Substituir o nome antigo por "Driverthu" em todas as telas, cabeçalhos, menus, textos, mensagens, notificações e configurações onde o nome do aplicativo aparecer, incluindo o nome exibido no ícone e no título do app. Não alterar funcionalidade, layout, cores ou componentes existentes.

## Estado atual do projeto
- O projeto é o template padrão da Emergent (Expo + FastAPI + MongoDB).
- Frontend: uma única tela (`app/index.tsx`) que exibe uma imagem; não há telas, cabeçalhos, menus ou textos com o nome antigo do app.
- O APK enviado (`passageiro-lipemobi.apk`) tem apenas 293 bytes — placeholder, não é um app funcional.
- Decisão do usuário: apenas configurar o nome "Driverthu" no template atual.

## Arquitetura
- Frontend: Expo Router (React Native)
- Backend: FastAPI + MongoDB (template default)

## Implementado (com datas)
- 2026-06: `app.json` → campo `expo.name` alterado de "frontend" para "Driverthu" (controla nome no ícone e título do app). `slug` e `bundleIdentifier`/`package` mantidos inalterados para não quebrar builds.

## Backlog (P1/P2)
- P1: Construir as telas reais do app (o usuário mencionou que pode descrever as telas ou pedir para recriar).
