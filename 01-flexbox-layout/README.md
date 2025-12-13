# Exercício 01 — Layout com Flexbox

Objetivo
- Praticar conceitos básicos de Flexbox para construir um layout simples: cabeçalho, barra de navegação, conteúdo principal com sidebar e rodapé.

Tarefas
1. Usar Flexbox para posicionar:
   - Cabeçalho (header) centralizado verticalmente.
   - Navbar horizontal com itens espaçados.
   - Main dividido em conteúdo principal (`.content`) e sidebar (`.sidebar`) lado a lado em desktop.
2. Tornar o layout responsivo:
   - Em telas menores que 700px a sidebar deve ficar abaixo do conteúdo principal.
3. Estilizar botões e links de forma consistente.

Critérios de aceitação
- O `header` deve estar fixado no topo (estilo simples).
- Em desktop, `.content` e `.sidebar` aparecem lado a lado (ex: 2fr / 1fr).
- Em mobile (<=700px) a `.sidebar` fica abaixo do `.content`.

Dicas / Hints
- Use `display: flex` e `flex-direction`, `gap`, `flex-basis` ou `flex` para controlar tamanhos.
- Para responsividade, use `@media (max-width: 700px) { ... }`.

Como testar
- Abra `index.html` e redimensione a janela.