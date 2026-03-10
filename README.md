Notebook Jupiter desenvolvido no Google Colab, como solução do Chalenge Telecon X Parte II


Este notebook tem como objetivo desenvolver, a partir dos dados limpos produzidos no desafio TELECON - PARTE I, um modelo em Machine Learning capaz de prever a evasão de clientes da empresa de telefonia e internet TELECOM X.


Para executar esse notebook é necessário carregar o arquivo CSV denominado "dados_limpos.csv" (também presente nesse repositório). Esse arquivo CSV contem um DataFrame contendo dados limpos e organizados produzidos no desafio anterior (Chalenge Telecon X Parte I). Este dataframe contem aproximadamente 7.000 registros de dados de clientes, com informações diversas tais como: tipo de contrato, valor mensal, serviços contratados, bem como informações pessoais dos clientes.


Dois novos tratamentos dos dados, não realizados na etapa anterior, são realizados neste notebook:
i) a transformação de variáveis categóricas não booleanas em variáveis booleanas usando o One Hot Encoder;
ii) a normalização dos dados numéricos, de forma a deixá-los na faixa de 0 a 1.


Este notebook executa os seguintes procesamentos:

1) Extração dos dados contidos no arquivo dados_limpos.csv, proveniente do notebook do desafio TELECON X PARTE I;
2) Transformação das variáveis categóricas não booleanas em variáveis booleanas, usando o One Hot Ecoding;
3) Normalização das escalas das variáveis explicativas numéricas;
4) Cálculo da correlação entre as variáveis explicativas e a variável alvo (evasão de clientes);
5) Eliminação de variáveis explicativas com pouca correlação com a variável alvo, sejam elas numéricas ou categóricas;
6) Separação dos dados de treinamento e teste;
7) Treinamento de diferentes modelos (além do modelo de base), e comparação dos desempenhos destes;
8) Seleção do melhor modelo;


Por fim, é apresentado um relatório contendo os principais resultados encontrados e sugestões de ações futuras.
