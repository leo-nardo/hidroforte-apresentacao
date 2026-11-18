# Hidroforte · O custo que ninguém mede

Apresentação scrollytelling (6 seções) sobre construir software internamente e as oportunidades de novos negócios para o grupo.

## Ver
Abra `index.html` no navegador e role a página (ou use o rail de progresso embaixo à esquerda).
Para servir localmente: `python3 -m http.server` e abra http://localhost:8000.

## Estrutura
- `index.html` — página única (HTML + CSS + JS, sem build)
- `assets/` — poses do personagem (PNG com fundo transparente, mesmo enquadramento)

## Como funciona
- Cada seção é uma camada fixa (`.stage`); o scroll controla opacidade/parallax e dispara as animações (`.act`).
- A pose do personagem muda por seção via classe `st1..st6` no `.pg`.
- Fonte do dado de 32%: McKinsey, The State of AI.
