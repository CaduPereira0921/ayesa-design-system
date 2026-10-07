# Sistema de design | Treinamento Ayesa x ibp solutions (WS03)

Sistema de design para gerar protótipos no Claude Design com a identidade visual do material do treinamento.

> **Aviso:** esta identidade foi criada a partir da paleta e da tipografia dos slides do curso. Não é o manual de marca oficial da Ayesa e não inclui o logo da empresa. Para usar a marca oficial, substitua os tokens e adicione os arquivos em `assets/`.

## Conteúdo
| Arquivo | Para quê |
|---|---|
| `tokens.css` | Variáveis de cor, tipografia, espaçamento e forma |
| `tokens.json` | Os mesmos tokens em formato neutro |
| `components.css` | Estilos de cabeçalho, card, indicador, botão, campo, tabela, selo e alerta |
| `preview.html` | Página que mostra todos os tokens e componentes |
| `guidelines.md` | Regras de uso e acessibilidade |
| `assets/` | Pasta para logo e imagens oficiais (vazia de propósito) |

## Como usar no Claude Design
1. Suba esta pasta em um repositório do GitHub.
2. No Claude Design, abra o seletor de sistema de design, escolha o sistema ainda vazio e configure a partir deste repositório (a Anthropic informa que dá para trazer sistemas de repositório do GitHub, arquivos de design ou uploads).
3. Selecione apenas este sistema no projeto e peça: `Aplique o sistema de design selecionado, mantendo estrutura e conteúdo.`
4. Confira o resultado contra `preview.html`.

## Substituir pela marca oficial
- Troque as cores em `tokens.css` e `tokens.json`.
- Coloque logo, fontes e imagens oficiais em `assets/`.
- Atualize `guidelines.md` e remova o aviso acima.
