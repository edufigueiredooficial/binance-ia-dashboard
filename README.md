# AGENTE BINANCE IA — Dashboard inicial

Envie `index.html` para a raiz do repositório público `binance-ia-dashboard`.

- Interface escura em português.
- Dados públicos da Binance Spot e USDⓈ-M Futures.
- Timeframes de 15m, 1h e 4h; EMA20/EMA50, RSI, ATR e volume relativo.
- Futures: funding, mark price e open interest quando disponíveis.
- Atualização a cada 60 segundos enquanto a página estiver aberta.
- Sem credenciais privadas, sem saldos de conta e sem execução de ordens.

## Limitações
Protótipo inicial, não sistema de trading validado. As regras são simplificadas e ainda não implementam todos os requisitos do comando mestre (estrutura completa de mercado, suportes/resistências, liquidações, sizing da posição, taxas, derrapagem e validação histórica). Relação risco/retorno é bruta e estimada. Não é monitoramento em segundo plano. A página depende da conectividade com endpoints públicos da Binance e de Chart.js via CDN. Repositório e site públicos tornam o código visível a qualquer pessoa; não publique segredos.
