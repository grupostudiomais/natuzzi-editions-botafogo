# Landing page · Natuzzi Editions Botafogo

Landing page de vendas da loja **Natuzzi Editions Casa e Gourmet Botafogo**, no Rio de Janeiro, feita para receber os clientes que chegam pelo tráfego pago.

Ela segue o manual de marca da Natuzzi Editions: marrom Pantone 477 C (#623B2A) com seus tons claros, títulos em caixa alta e barra vertical ao lado dos títulos.

## Estrutura

```
index.html   → a página inteira (HTML e CSS em um único arquivo)
assets/      → logo, fotos e textura de fundo
```

## Seções

1. Cabeçalho com logo e botão de WhatsApp
2. Abertura com foto principal e chamadas para visita
3. Destaques da marca (desde 1959, Puglia, feito à mão)
4. A marca
5. Por que Natuzzi Editions
6. Destaques: Leggiadro, Premura, Fascino, Lima, Amorevole e Batticuore
7. O showroom
8. Visite: endereço, WhatsApp, Google Maps e Instagram
9. Chamada final e rodapé

Todos os botões abrem o WhatsApp da loja, **(21) 99567-4337**, com uma mensagem pronta. Nos produtos, a mensagem já inclui o nome do modelo.

## Pendências antes de publicar

- [ ] Preencher o horário de funcionamento (procure por `[HORÁRIO DE FUNCIONAMENTO]` no `index.html`).
- [ ] Instalar as fontes oficiais **Söhne** e **Söhne Schmal**, licenciadas pela Klim Type Foundry. Enquanto elas não forem instaladas, a página usa as alternativas gratuitas Inter e Barlow Condensed, do Google Fonts.
- [ ] Confirmar com a loja quais recursos opcionais dos produtos são vendidos no Brasil (relax, Dual Power, Triple-Motion, USB).
- [ ] Incluir os códigos de rastreamento das campanhas, como Meta Pixel e Google Tag, antes de `</head>`.

## Como publicar

Por ser um site estático, ele pode ser publicado em qualquer hospedagem simples, como GitHub Pages, Netlify, Vercel ou a hospedagem atual do domínio.
