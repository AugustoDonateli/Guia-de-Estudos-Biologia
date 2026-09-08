# Guia de Estudos — Biologia

Guias de estudo interativos em HTML, feitos para provas específicas.
Cada guia é um arquivo único, sem dependências além das fontes do Google Fonts,
e funciona offline depois de carregado.

## Guias

| Arquivo | Tema |
|---|---|
| [`index.html`](index.html) | **Morfologia vegetal** — guia completo da prática |
| [`cola-de-bancada.pdf`](cola-de-bancada.pdf) | Material de consulta para levar à prática — 4 páginas A4 |

### `index.html` — Bancada de Morfologia Vegetal

Organizado como curso, não como resumo de prova: um módulo por grupo, na ordem
evolutiva, com teoria própria. A prática do ano anterior entra só no fim, como
calibragem do estilo de cobrança.

**Estrutura**

1. Célula — o que significam n e 2n, mitose e meiose, com comparador
   passo a passo, e por que em planta a meiose faz esporo e a mitose faz gameta
2. A lógica das plantas terrestres — a sequência das inovações
3. Bancada e microscopia — instrumentos, regras de desenho, checklist
4. a 7. Uma seção por estação da prática: resumo + `aprofundar` expansível, ciclo de vida
   navegável, lâminas interativas do grupo, o que costuma ser cobrado, questões
8. Comparações — os quatro grupos, mono × eudicot, síndromes de polinização
9. O padrão do professor — a prática do ano anterior e as trocas mais prováveis
10. Treino — identificação com todas as lâminas e discursivas de síntese
11. Glossário com busca
12. Cola de bancada — as 4 páginas A4 de consulta, com CSS de impressão

**Recursos**

- 14 lâminas em SVG com pinos clicáveis e modo prova (quiz com placar e recorde)
- Comparador de mitose × meiose em 5 e 8 passos, com contador de ploidia
- 4 ciclos de vida passo a passo, com ploidia e destaque de meiose e fecundação
- 18 questões discursivas com corretor de palavras-chave e gabarito modelo
- Tema claro/escuro e progresso salvos no navegador (`localStorage`)
- Cola de bancada em 4 páginas A4, com `@media print` que imprime só ela

### `cola-de-bancada.pdf`

Gerado a partir da seção 11 do guia (`.folha` × 4), em A4 com margens de 10 mm.
Para regerar após alterar o conteúdo, renderize `index.html` em mídia `print`.
Página 1 método e comparativo · 2 musgo e samambaia · 3 pinheiro e a flor ·
4 respostas modelo, tabelas e glossário.

## Convenções

- Um arquivo HTML autocontido por guia: CSS, JS, dados e SVGs no mesmo arquivo
- Sem build, sem dependências instaladas — abrir no navegador basta
- Conteúdo em português do Brasil
- Widgets montados por JS em `<div data-mount="...">`, para reaproveitar
  o mesmo componente em vários módulos
