# Churn funcionários

## Descrição

Este projeto se concentra em prever o churn de funcionários usando técnicas de análise de dados e aprendizado de máquina. O churn de funcionários refere-se à rotatividade de funcionários dentro de uma empresa, e a capacidade de prever essa rotatividade pode ajudar as empresas a tomar medidas proativas para melhorar a retenção de funcionários.

## Objetivo

 * Prever a probabilidade de um funcionário deixar a empresa.
 * Identificar os principais indicadores que influenciam a decisão de um funcionário de sair.
 * Sugerir políticas ou estratégias para melhorar a retenção de funcionários.

##  Estrutura do Projeto
1 Exploração e Análise de Dados (EDA)

 * Carregamento e visualização dos dados.
 * Análise estatística e gráfica das variáveis.
 * Identificação de correlações entre variáveis.
 * Pré-processamento de Dados

2 Tratamento de dados ausentes.
 * Codificação de variáveis categóricas.
 * Normalização/Padronização de dados.
 * Modelagem

3 Separação dos dados em conjuntos de treinamento e teste.
 * Treinamento de vários modelos de aprendizado de máquina (Regressão Logística, Random Forest, etc.).
 * Avaliação dos modelos usando métricas como AUC e acurácia.
 * Otimização de Hiperparâmetros

4 Uso de GridSearchCV para encontrar os melhores parâmetros para os modelos.
 * Comparação de desempenho entre modelos otimizados.
 * 
5 Implementação
 * Implementação do modelo final em um pipeline de previsão.
 * Sugestão de um plano estratégico de retenção baseado nos insights obtidos.

## Resultados
### Conclusões da Análise Exploratória de Dados (EDA)
 * Correlações Positivas: Performance Rating, Monthly Rate, Num Companies Worked, Distance From Home.
 * Correlações Negativas: Total Working Years, Job Level, Years In Current Role, Monthly Income.
Outras Observações:
 * Empregados solteiros têm maior proporção de desligamentos.
 * Funcionários que trabalham frequentemente fora do horário têm maior proporção de desligamentos.
 * Funcionários que residem longe do trabalho têm maior proporção de desligamentos.
   
## Melhor Modelo
O modelo de Regressão Logística ajustado apresentou um AUC mais alto em comparação com o Classificador Random Forest.

## Plano de Retenção Estratégica
### Indicadores de Churn:

 * Renda Mensal: Salários mais altos estão associados a menores taxas de desligamento.
 * Horas Extras: Funcionários que trabalham horas extras são mais propensos a deixar a empresa.
 * Anos com o Atual Gerente: Alta rotatividade pode ocorrer após 6 meses com um novo gerente.
   
Sugestões:

 * Realizar reuniões presenciais com funcionários de risco médio e alto para discutir as condições de trabalho.
 * Revisar a estrutura organizacional e oferecer treinamentos de gerenciamento.
 * Oferecer suporte em transporte ou auxílio-transporte para funcionários que residem longe do trabalho.
