# Diretrizes de uso | Sistema de design do treinamento

## Princípios
- **Navy conduz, amarelo destaca.** Navy para títulos, cabeçalhos e itens principais. Amarelo só para o que está ativo, é destaque ou é a ação principal.
- **Visual por tipo de conteúdo.** Escolha o formato (tabela, cards, fluxo) pelo que está sendo mostrado, não por padrão.
- **Sem verde.** O verde foi retirado da paleta. Status usa navy, amarelo e tons claros, sempre com texto junto da cor.
- **Cantos retos e bordas tracejadas** nos painéis e cards.
- **Pouco texto na tela.** Quando houver bullets, frases curtas.

## Tipografia
- Família: Calibri (fallback Carlito, Segoe UI, Arial).
- Eyebrow: 13 px, negrito, caixa alta, espaçamento de letras de 2 px, azul.
- Título: 30 px, negrito, navy.
- Corpo: 15 px, cor de texto #333.

## Componentes disponíveis
Cabeçalho de página, card (normal, ativo, inativo), indicador (KPI), botão (primário, secundário, desabilitado), campo, tabela, selo de status (ok, pendente, falha), alerta de lacuna e barra de progresso. Veja `preview.html`.

## Acessibilidade
- Nunca comunicar status só por cor: o selo sempre traz o rótulo (Gerado, Pendente, Falha).
- Foco visível em botões e campos (contorno azul de 3 px).
- Texto sobre navy deve ser branco; texto sobre amarelo deve ser navy.

## Escopo
Este sistema foi extraído da identidade visual do material do treinamento WS03. Não reproduz o logo nem o manual de marca oficial da Ayesa.
