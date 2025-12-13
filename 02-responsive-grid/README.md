# Exercício 02 — Grid Responsivo

Objetivo
- Construir um layout de galeria de cards usando CSS Grid, com comportamento responsivo em diversas larguras.

Tarefas
1. Criar uma grade de cards responsiva:
   - Desktop (>=1000px): 4 colunas
   - Tablet (700px–999px): 2 colunas
   - Mobile (<700px): 1 coluna
2. Garantir espaçamento consistente (gap) entre cards.
3. Fazer cards com altura uniforme e conteúdo centralizado verticalmente.

Critérios de aceitação
- A grid se adapta conforme os breakpoints.
- Cards têm sombra leve e bordas arredondadas.
- Texto dentro do card está legível e centralizado.

Dicas
- Use `display: grid` e `grid-template-columns: repeat(auto-fit, minmax(...))` ou media queries.
- Use `aspect-ratio` (se suportado) ou padding-trick para manter altura consistente.

Como testar
- Abra `index.html` e redimensione a janela.