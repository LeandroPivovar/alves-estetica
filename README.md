# Alves Estética Automotiva

Site institucional da Alves Estética Automotiva (antigo Lava Rápido Premier 2). HTML/CSS/JS estático, sem build.
Mesma estrutura do site da MRA Estética Automotiva, com a identidade da Alves: preto, azul elétrico e prata,
e o nome "Alves" em letra cursiva como na logo.

```bash
npx --yes serve . -l 6450
```

## Estrutura

```
index.html
assets/
  css/styles.css
  js/main.js              menu mobile, formulário -> WhatsApp, FAQ, reveal ao rolar, ano do rodapé
  fonts/phosphor/         ícones Phosphor (woff2 local, licença MIT)
  img/favicon.svg
```

Sem logo em arquivo nem fotos: a marca é texto e o hero tem a silhueta de um carro em SVG.

## Dados usados (fonte: perfil e capa do WhatsApp Business)

| Campo | Valor |
|---|---|
| Nome | Alves Estética Automotiva |
| Slogan | Seu veículo merece |
| Capa | "O Lava Rápido Premier 2 agora é Alves Estética Automotiva" / "Limpeza detalhada requer tempo e qualidade" / "Processos feitos com..." / "Produtos premium de..." |
| WhatsApp | (88) 99224-6478 (`wa.me/558892246478`, constante `WA` no `main.js`) |
| Horário | Sábado, 08:00 às 16:00 (único dia visível no print) |
| Veículos | A logo mostra carro e moto |

## Confirmar com o cliente

- **Horário dos outros dias:** o print só mostra o sábado (8h às 16h). O site diz "outros dias: consulte".
- **Serviços:** a capa fala só em "limpeza detalhada". Os cards (lavagem detalhada, lavagem de motos, limpeza
  interna) são os básicos. Pegar a lista real (higienização, polimento, vitrificação, enceramento, motor...).
- **Endereço e cidade:** não informados (DDD 88, interior do Ceará). Com o endereço dá para incluir mapa.
- **Telefone:** o perfil mostra `9224-6478`. O `wa.me` usa o número do perfil; o texto exibido e o `tel:` usam
  `(88) 99224-6478`, com o 9 do celular.
- **Frases da capa:** as legendas dos ícones aparecem cortadas ("Processos feitos com...", "Produtos premium
  de..."). O site usa "Processos feitos com calma" e "Produtos premium".
- **Logo e fotos:** pedir a logo em arquivo e fotos de veículos atendidos (antes e depois).

## Depoimentos

Não foram incluídos, para não publicar avaliações inventadas.

Fontes: Saira, Manrope e Yellowtail (Google Fonts, OFL / Apache).
