# PicPay_Case
Resolução do Case do PicPay para discussão com lideranças.

## Ordem
1. No Notebook 01.EDA_Feature_Selection, temos uma análise exploratória das variáveis ao longo das safras, analisando correlação Person entre as variáveis, a distruição das mesmas ao longo das safras, seu respectivo preenchimento e a estabilidade ao longo de toda a base.Além disso, 3 métodos de seleção de variáveis (Correlação com Information Value, Random Forest e RFE foram utilizados inicialmente, sendo que um deles foi descartado na etapa de modelagem e os outros dois fizeram a seleção das mesmas variáveis. 
2. No Notebook 02.Modelo_Reg_Logística, construímos o nosso modelo de base, ou seja, o modelo mais simples que utilizaremos como base para avaliar a construção de modelos mais complexos.
3. No Notebook 02.Modelo_Reg_Logística_Final, refinamos o modelo criado, utilizando apenas variáveis que possuíam coeficientes diferente de 0. Esse é o nosso modelo de base.
4. No Notebook 03.Modelo_XGBoost, construímos um modelo utilizando ensemble de árvores de decisão (XGBoost) com otimização de hiperparâmetros utilizando HyperOpt. A utilização de XGBOOST trouxe ganhos significativos de performance.

Em todos os notebooks de modelos, ao final temos duas células de avaliação das variáveis ao longo das safras utilizando o PSI, garantindo a observabilidade do modelo futuramente.
