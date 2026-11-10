# RE/MAX PRO — site

Conceito de site para a agência RE/MAX PRO, na Rua Júlio Dinis, 849, Porto.

Página estática única: abre o `index.html` no browser, sem build nem dependências. A fonte (Manrope) vem do Google Fonts.

## Estrutura

- `index.html`: página completa (HTML, CSS e JavaScript)
- `assets/fachada.jpg`: foto da fachada, usada no banner principal
- `assets/equipa.jpg`: foto da equipa
- `assets/balao.svg`: balão RE/MAX PRO, usado como favicon

## Conteúdo

O conteúdo vem da página da agência no remax.pt. Os imóveis, as contagens (288 à venda, 26 para arrendar) e os links dos anúncios são os que lá estavam publicados em novembro de 2026 e estão escritos à mão no `index.html`; para os atualizar, edita o objeto `D` no script.

O letreiro "Aberto / Fechado" calcula o estado a partir do horário da agência, na hora de Lisboa.

## Publicar

Para pôr online com GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.

---
Conceito de design · proposta não oficial.
