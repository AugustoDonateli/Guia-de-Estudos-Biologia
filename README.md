# Guia de Estudos — Biologia

Guias de estudo interativos em HTML, feitos para provas específicas.
Cada guia é um arquivo único, sem dependências além das fontes do Google Fonts,
e funciona offline depois de carregado.

## Guias

| Arquivo | Tema |
|---|---|
| [`index.html`](index.html) | **Morfologia vegetal** — briófitas, pteridófitas, gimnospermas e angiospermas |

### `index.html` — Bancada de Morfologia Vegetal

Organizado como curso, não como resumo de prova: um módulo por grupo, na ordem
evolutiva, com teoria própria. A prática do ano anterior entra só no fim, como
calibragem do estilo de cobrança.

**Estrutura**

1. Fundamentos — a lógica das plantas terrestres, alternância de gerações, ploidia
2. Bancada e microscopia — instrumentos, regras de desenho, checklist
3. a 6. Um módulo por grupo: resumo + `aprofundar` expansível, ciclo de vida
   navegável, lâminas interativas do grupo, o que costuma ser cobrado, questões
7. Comparações — os quatro grupos, mono × eudicot, síndromes de polinização
8. O padrão do professor — a prática do ano anterior e as trocas mais prováveis
9. Treino — identificação com todas as lâminas e discursivas de síntese
10. Glossário com busca

**Recursos**

- 14 lâminas em SVG com pinos clicáveis e modo prova (quiz com placar e recorde)
- 4 ciclos de vida passo a passo, com ploidia e destaque de meiose e fecundação
- 18 questões discursivas com corretor de palavras-chave e gabarito modelo
- Tema claro/escuro e progresso salvos no navegador (`localStorage`)

## Convenções

- Um arquivo HTML autocontido por guia: CSS, JS, dados e SVGs no mesmo arquivo
- Sem build, sem dependências instaladas — abrir no navegador basta
- Conteúdo em português do Brasil
- Widgets montados por JS em `<div data-mount="...">`, para reaproveitar
  o mesmo componente em vários módulos
