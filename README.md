# Jogos de Matemática — 6º e 7º ano

Três jogos educativos de Matemática para usar em sala de aula, em equipe, num computador, tablet, celular ou tela projetada. Cada jogo tem um **modo 6º ano** e um **modo 7º ano**, que é mais difícil.

| Pasta | Jogo | Conteúdos do 6º ano | Conteúdos do 7º ano |
|---|---|---|---|
| `escape-room-matematico/` | Escape Room: O Mistério da Escola | frações equivalentes e comparação, decimais, múltiplos e divisores, perímetro e área | números inteiros, razão e proporção, porcentagem, equações de uma etapa |
| `construa-sua-cidade/` | Construa sua Cidade | área e perímetro, conversão de medidas, decimais, leitura de tabela | escala, porcentagem, razão e proporção, comparação de custos |
| `feira-das-boas-escolhas/` | Feira das Boas Escolhas | dinheiro e decimais, troco, frações de quantidades, tabela de preços e estoque | desconto e acréscimo, proporção em receitas, comparação de ofertas, lucro |

A pasta `corrida-decimais-fracoes/` é um jogo anterior e serviu só de referência. Ela não foi alterada.

## Como abrir

1. Abra a pasta do jogo.
2. Dê dois cliques no arquivo `index.html`. Ele abre no navegador (Chrome, Edge, Firefox ou Safari).

Não precisa instalar nada nem ter internet. Cada jogo é um único arquivo, sem bibliotecas externas.

Para projetar na sala, use o navegador em tela cheia (tecla `F11`).

## Tutoriais
Cada pasta tem um arquivo `tutorial.html`, que também abre com dois cliques. Ele traz o passo a passo do jogo, exemplos resolvidos, a pontuação, as dúvidas comuns e uma seção para o professor. Também dá para abrir o tutorial pelo botão "📘 Ver o tutorial completo", na tela inicial de cada jogo.

## Como jogar

### 🔦 Escape Room Matemático — O Mistério da Escola
A Taça da Gincana sumiu! A equipe passa por 4 salas: Biblioteca, Laboratório, Quadra e Sala da Direção.
- Cada sala tem um desafio. Acertou? A equipe ganha uma **pista** e avança.
- Errou? O jogo explica um jeito de pensar e a equipe tenta de novo. No 2º erro, mostra a resolução completa.
- A equipe tem **3 dicas** para a partida inteira. Usar dica não impede de continuar.
- No final, as 4 pistas são propriedades matemáticas (por exemplo, "é múltiplo de 3"). Elas permitem descobrir em qual armário está a taça. Só um armário combina com todas as pistas.
- Cada sala sugere papéis que vão mudando: Leitor(a), Calculista e Conferente.
- **Banco de desafios:** há de 4 a 5 desafios validados por sala e por ano, além de 3 mistérios finais por ano. Em "Jogar de novo", cada sala recebe um desafio diferente do anterior.
- **Pontos:** 10 por sala, +2 por sala resolvida sem dica e +5 por achar o armário de primeira. Errar não tira pontos.

### 🏙️ Construa sua Cidade
A equipe planeja uma cidade em um terreno de 10 × 10 quadradinhos, com orçamento em moedas (🪙).
- Escolham uma construção na lista e cliquem num quadradinho. Ele vira o **canto de cima, à esquerda** da construção. Não é preciso arrastar nada.
- O jogo não deixa construir fora do terreno nem por cima de outra construção, e explica o motivo.
- Use **Desfazer**, **Remover** ou **Limpar terreno** à vontade: experimentar não tira pontos.
- Cada rodada tem objetivos. Quando um objetivo é cumprido, a equipe responde uma **pergunta de conferência** com o cálculo feito a partir da própria cidade (área, perímetro, gasto, escala, porcentagem...). Se a cidade mudar depois, o jogo pede para conferir de novo.
- Antes de finalizar, aparece um **resumo dos cálculos**.
- **Pontos:** 10 por objetivo conferido, +5 se a conta saiu certa de primeira e +10 se o orçamento foi respeitado.
- Pelo teclado: Tab até o terreno, setas para andar pelos quadradinhos e Enter para construir.

### 🧺 Feira das Boas Escolhas
A equipe cuida de uma barraca com caixa inicial de R$ 50,00 e um estoque de produtos.
- Chegam 8 clientes, um de cada vez. Para cada um: separar os itens (+ e −), calcular o total e, se pagar em dinheiro, o troco.
- Valores podem ser digitados como `12,50`, `12,5` ou `R$ 12,50`.
- O estoque nunca fica negativo. Se o cliente pedir mais do que existe, o jogo explica.
- No 7º ano, cada cliente informa se o desconto é aplicado no preço de cada unidade (antes de multiplicar) ou no total (depois de somar).
- Há 2 eventos opcionais: uma promoção e uma reposição de estoque.
- O relatório final separa **receita**, **custo dos produtos vendidos**, **lucro**, **gastos com estoque** e **troco**, e confere o caixa.

## Privacidade e salvamento
- Nenhum jogo pede nome, e-mail, senha ou outro dado pessoal. Não há compras, prêmios reais nem coleta de dados.
- O progresso (partida em andamento e últimos 5 resultados) fica salvo **somente no navegador daquele aparelho**, em `localStorage`, com uma chave diferente para cada jogo:
  - `mat-escape-room-v1`
  - `mat-construa-cidade-v1`
  - `mat-feira-boas-escolhas-v1`
- Cada jogo tem um botão "Apagar progresso salvo neste aparelho" na tela inicial.

## Acessibilidade
- Botões grandes, foco visível ao navegar com Tab e mensagens lidas por leitores de tela (`aria-live`).
- Acerto, erro e seleção são mostrados com texto e ícones (✔ ✖ ⚠️), não só com cores.
- As animações são desligadas quando o sistema está com "reduzir movimento" ativado.
- Não há sons.
- O layout foi testado em telas de 360 px de largura.
