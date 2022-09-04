# Projeto-Analise-de-Compra-e-Venda-Petroleo-Gas
 
# Análise de Compra e Venda das Ações
Dados de Petróleo e Gás e que lidam com a Exploração, Refino e Distribuição

RRRP: 3R PETROLEUM ÓLEO E GÁS S.A <br />
CSAN: COSAN S.A. <br />
DMMO: DOMMO ENERGIA S.A. <br />
ENAT: ENAUTA PARTICIPAÇÕES S.A. <br />
PRIO: PETRO RIO S.A. <br />
PETR: PETROLEO BRASILEIRO S.A. PETROBRAS <br />
RECV: PETRORECÔNCAVO S.A. <br />
RPMG: REFINARIA DE PETROLEOS MANGUINHOS S.A. <br />
UGPA: ULTRAPAR PARTICIPACOES S.A. <br />
VBBR: VIBRA ENERGIA S.A. <br />

# Estratégia de Desenvolvimento
1. Simular uma estratégia (backtest) de compra e venda usando as Bandas de Bollinger para as empresas do setor listadas na bolsa. Para o backtest, use o período mínimo de 1 ano.

1. Instalação de Bibliotecas.
2. Importação das Bibliotecas.
2. Criação de uma função chamada "importa_acao" que vai importar os dados de uma das ações da lista acima no perído de 1 ano.
3. Criação de uma função chamada "calculos_principais" que fará cálculos importantes para o plot do Gráfico de Bollling.
4. Criação de uma função chamada "grafico_bollinger" que cria o gráfico de Bollinger.
5. Criação de uma função chamada "executa_funcoes_bollinger" ela chama todas as outras funções acima e executa o Backtesting utilizando as Bandas de Bollinger.
2. Fazer uma análise exploratória com o objetivo de levantar hipóteses e entender as variações de preço do setor.

1. Criação de uma função chamada "compara_acoes" essa função vai comparar o preço de cada ação.
2. Criar um gráfico que compara o preço de todas as ações:
3. Analizar os Quartis, a Média, a Mediana e o Desvio Padrão de cada ação.
4. Gerar gráficos bloxplots para identificar outliers.
5. Identificar qual ação tem maior variação de Preço (Ação com Maior Risco de Investimento).
6. Hipótese 1: Os títulos com retornos positivos no último ano darão retornos positivos no próximo mês?
3. Selecionar ou criar uma nova estratégia baseada em suas análises.

1. Gerar os gráficos de Bolling de compra e venda de Ações das previsões.
2. Mostrar esses dados de compra e venda comparando as ações em um único gráfico
3. Identificar quais ações tiveram o maior lucro baseando-se na estratégia de Backtest usando as Bandas de Bollinger
4. Comparar e analisar a performance das duas estratégias nas empresas do setor.

1. Escolher qual é ação é a mais lucrativa comprar com base nos resultados do modelo e das análises anteriores.


## Conclusões
De acordo com a estratégia de backtest usando as Bandas de Bollinger as ações que dão mais lucro são: <br />

RRRP: 71.022 <br />
UGPA: 45.889 <br />
ENAT: 44.913 <br />
De acordo com a estratégia de backtest usando as Bandas de Bollinger as ações que dão mais prejuízo são: <br />

VBBR: -20361 <br />
RPMG: -13.554 <br />
PRIO: -4.019 <br />
De Acordo com as análises estatísticas de preços as ações com as maiores variações de preços são: <br />

PETR <br />
RRRP <br />
RECV3 <br />
A escolha das ações pode se basear no lucro obtido e na variação de preço: <br />

Se for um investidor arrojado ele pode investir na RRRP e ter altos lucros, porém correndo um risco maior de perda já que essa carteira tem uma variação maior de preço; <br />
Uma excelente opção de investimento para um perfil mais conservador é a carteira UGPA3 que tem uma variação menor de preços e retorna bons lucros. <br />
Em segundo lugar para investimentos temos a ENAT que retorna bons lucros porém com uma variação de preço moderada. <br />
As ações VBBR, RPMG e PRIO devem ser evitadas já que dão prejuízo <br />
