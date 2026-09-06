# Guia de Estudos — Biologia

Guias de estudo interativos em HTML, feitos para provas específicas.
Cada guia é um arquivo único, sem dependências além das fontes do Google Fonts,
e funciona offline depois de carregado.

## Guias

| Arquivo | Tema | Conteúdo |
|---|---|---|
| [`index.html`](index.html) | **Morfologia vegetal** — aula prática | Briófitas, pteridófitas, gimnospermas e angiospermas |

### `index.html` — Bancada de Morfologia Vegetal

Construído sobre a prática do ano anterior (musgo, soros de samambaia,
lâminas nº 40 e nº 41 de pinheiro, flor de *Hibiscus* e lâmina nº 44 de polens).

- **11 lâminas interativas** em SVG, com pinos clicáveis, painel de legenda
  e um **modo prova** com quiz de identificação e placar
- **4 ciclos de vida** navegáveis passo a passo, com ploidia e destaque
  de meiose, fecundação e dependência de água
- **18 questões discursivas** com corretor de palavras-chave
- Tabelas comparativas, síndromes de polinização, protocolo de bancada
  e glossário com busca
- Tema claro/escuro e progresso salvos no navegador (`localStorage`)

## Convenções

- Um arquivo HTML autocontido por guia: CSS, JS, dados e SVGs no mesmo arquivo
- Sem build, sem dependências instaladas — abrir no navegador basta
- Conteúdo em português do Brasil
- Estado do usuário (respostas, checklist, placar, tema) em `localStorage`,
  com prefixo próprio por guia
