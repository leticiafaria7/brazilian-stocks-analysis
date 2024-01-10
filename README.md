# Análises das ações do índice Ibovespa

> 💡 Este repositório tem como objetivo realizar a análise da variação dos preços das principais ações do índice Ibovespa.

Para escolher quais ações seriam analisadas, [este link](https://br.tradingview.com/heatmap/stock/#%7B%22dataSource%22%3A%22IBOV%22%2C%22blockColor%22%3A%22change%22%2C%22blockSize%22%3A%22market_cap_basic%22%2C%22grouping%22%3A%22sector%22%7D) traz um treemap com o tamanho da influência que cada ação tem no índice.

Sendo assim, as ações escolhidas para análise foram:
Financeiro | Energia | Indústria | Comunicações | Varejo
--- | --- | --- | --- | ---
ITUB4 | PETR3 | ABEV3 | VIVT3 | LREN3
RENT3 | CMIG4 | VALE3 | | MGLU3
MULT3 | | SUZB3 | | 

## Final do código
Estes números no final dos códigos (tickets) das ações possuem os seguintes significados:

Código | Tipo | Explicação
--- | --- | ---
3 | Ordinárias | Dão direito ao voto na assembleia para quem é acionista
4 | Preferenciais | Dão preferência aos acionistas no recebimento de dividendos
5 | Preferenciais Classe A | Maior preferência
6 | Preferenciais Classe B | Preferência menor que da classe A
F | Fracionado | Comprar ações por unidades em vez de lotes
11 | BDRs <br> ETFs <br> Units | Brazilian Deposits Receipts (ações de empresas estrangeiras) <br> Exchange Traded Funds (fundos de índices) <br> ativos compostos por mais um tipo de ação

As empresas que possuem só final do tipo 3 não divide as preferências no recebimento de dividendos. <br> Quanto mais ações com tipos diferentes, maior a divisão entre os acionistas.

## Dados
Os dados das cotações foram obtidos [neste site](https://www.infomoney.com.br/cotacoes/b3/acao/).

Há dados diários desde 02/01/2018.

As informações disponíveis são:
- Data
- Abertura
- Fechamento
- Variação
- Mínimo
- Máximo
- Volume

## Análises
A descrição das análises estará neste bloco
