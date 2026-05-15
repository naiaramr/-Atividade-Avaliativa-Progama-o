📈 Análise de Ações — Empresas Brasileiras na B3

Análise histórica do desempenho de quatro grandes empresas listadas na B3 no período de janeiro de 2023 a maio de 2026, com Python e dados do Yahoo Finance.


🎯 Objetivo
Avaliar o comportamento histórico das ações de quatro importantes empresas brasileiras ao longo de aproximadamente três anos e meio, calculando métricas estatísticas de desempenho — média anual, desvio-padrão anual e retorno semestral — e visualizando a evolução dos preços de fechamento com marcação por semestre.

🏢 Empresas Analisadas
EmpresaTickerSetorVale S.A.VALE3.SAMineraçãoAmbev S.A.ABEV3.SABebidas / ConsumoItaú UnibancoITUB4.SAFinanceiro / BancárioBanco do BrasilBBAS3.SAFinanceiro / Bancário

📅 Período Analisado
01 de janeiro de 2023 → 14 de maio de 2026

🗂️ Estrutura do Projeto
analise-acoes-b3/
├── analise_4_empresas_brasileiras.py   # Script principal de análise
└── README.md                           # Este arquivo

⚙️ Como Executar
Pré-requisitos: Python 3.8+ e conexão com a internet.
Instale as dependências:
bashpip install yfinance pandas matplotlib seaborn
Execute o script:
bashpython analise_4_empresas_brasileiras.py
Alternativa recomendada — Google Colab:

Acesse colab.research.google.com
Crie um novo notebook, cole o script e execute com Ctrl + Enter


As quatro bibliotecas já vêm pré-instaladas no Colab, sem necessidade de instalação adicional.


🛠️ Tecnologias Utilizadas
BibliotecaUso principalyfinanceDownload dos dados históricos da B3 via Yahoo FinancepandasManipulação e análise dos DataFramesmatplotlibGeração dos gráficos de linha (painel com 4 subplots)seabornEstilização dos gráficos (tema darkgrid)
Linguagem: Python 3.8+ · Fonte de dados: Yahoo Finance

📊 O Que o Script Produz
Para cada empresa, o script calcula e exibe:

As 5 primeiras e 5 últimas linhas do DataFrame (Abertura, Máxima, Mínima, Fechamento, Volume)
Média anual do preço de fechamento (2023, 2024, 2025 e 2026*)
Desvio-padrão anual do preço de fechamento
Retorno semestral — variação % entre semestres consecutivos (ex: 2023-S1 → 2023-S2)
Gráfico de linha com eixo X semestral e destaque nos pontos de fim de semestre
Tabela resumo semestral com abertura, fechamento, média, desvio, mínimo, máximo e retorno por semestre

Ao final, gera um painel único com os 4 gráficos salvo como grafico_empresas_brasileiras.png.
*2026 compreende apenas o período de janeiro a 14 de maio.

📋 Resultados Encontrados
Vale S.A. — VALE3
IndicadorValorPreço inicial (jan/2023)R$ 87,69Preço final (mai/2026)R$ 83,87Retorno total no período-4,36%Faixa 52 semanasR$ 44,81 – R$ 91,62
A Vale apresentou trajetória volátil ao longo do período, fortemente atrelada aos preços do minério de ferro no mercado internacional. A desaceleração da economia chinesa em 2024 pressionou as cotações, que se recuperaram parcialmente em 2025-2026 com novos projetos de cobre e perspectivas de retomada da demanda global. No 4T25, a empresa registrou prejuízo líquido de R$ 21 bilhões, impactado por impairment de ativos de níquel.

Ambev S.A. — ABEV3
IndicadorValorPreço inicial (jan/2023)R$ 14,62Preço final (mai/2026)R$ 15,75Retorno total no período+7,73%Faixa 52 semanasR$ 11,68 – R$ 16,77
A Ambev encerrou o período com leve valorização, mas com percurso irregular. Ao longo de 2024, a ação chegou a mínimas de R$ 11,68, pressionada pelo ambiente de juros elevados e desaceleração do consumo. A recuperação se deu em 2025-2026 — em maio de 2026, as ações subiram cerca de 11% em um único pregão após o 1T26 superar as expectativas, com EBITDA ajustado de R$ 7,5 bilhões.

Itaú Unibanco — ITUB4
IndicadorValorPreço inicial (jan/2023)R$ 21,85Preço final (mai/2026)R$ 47,79Retorno total no período+118,72%Faixa 52 semanasR$ 27,35 – R$ 49,33
O Itaú foi o grande destaque do grupo, mais que dobrando de valor no período. A instituição manteve o maior ROE entre os grandes bancos brasileiros (próximo de 24% em 2025), com carteira de crédito acima de R$ 1,4 trilhão e inadimplência controlada em torno de 1,9%. O lucro líquido atingiu R$ 11,9 bilhões no 4T25, com crescimento de 9,9% na comparação anual.

Banco do Brasil — BBAS3
IndicadorValorPreço inicial (jan/2023)R$ 44,35Preço final (mai/2026)R$ 20,81Retorno total no período-53,08%Cotação no início de 2026R$ 21,92
O Banco do Brasil registrou o pior desempenho do grupo, com queda superior a 50%. A deterioração da carteira de agronegócio ao longo de 2024-2025 elevou provisões e comprimiu o lucro, com ROE caindo para 7,3% no 1T26 — o menor entre os grandes bancos listados. Analistas revisaram o preço-alvo para a faixa de R$ 23-25 em 2026, condicionando a recuperação à normalização da carteira rural.

Comparativo Geral (Jan/2023 → Mai/2026)
EmpresaTickerJan/2023Mai/2026Retorno TotalRankingItaú UnibancoITUB4R$ 21,85R$ 47,79+118,72%🥇 1ºAmbev S.A.ABEV3R$ 14,62R$ 15,75+7,73%🥈 2ºVale S.A.VALE3R$ 87,69R$ 83,87-4,36%🥉 3ºBanco do BrasilBBAS3R$ 44,35R$ 20,81-53,08%4º

Os retornos consideram apenas a variação do preço de fechamento e não incluem dividendos distribuídos no período. Itaú e Ambev pagaram proventos relevantes, o que elevaria ainda mais o retorno total para o acionista.
