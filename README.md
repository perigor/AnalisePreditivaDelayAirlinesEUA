# Análise de Dados de Atrasos de Voos de CIAs Aéreas dos EUA 

![The-plane-flying-at-sunset-airliner-photography_2560x1600](https://github.com/perigor/AnalisePreditivaDelayAirlinesEUA/assets/133716998/603ec2ba-e696-4a7d-99b4-2e02546e7f54)


**Introdução:**

Recentemente, dando continuidade nos meus estudos, mergulhei em um conjunto de dados público disponível no Kaggle, fornecendo uma visão abrangente do tráfego aéreo. Embora o conjunto de dados não tenha uma data específica, ele se torna uma referência para comparações, permitindo-nos explorar e compreender o cenário do tráfego aéreo contemporâneo.

Base de Dados Kaggle: https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay/data

**O Tráfego Aéreo em Números (Dados de 2023):**

Diariamente, a Organização de Tráfego Aéreo (ATO) da FAA atende a mais de 45.000 voos e transporta cerca de 2,9 milhões de passageiros de companhias aéreas. Este serviço é prestado em uma extensão impressionante de mais de 29 milhões de quilômetros quadrados de espaço aéreo. Todo esse ecossistema culmina em um faturamento anual de nada menos que $488 bilhões.

Administração Fedeal de Aviação EUA: https://www.faa.gov/air_traffic/by_the_numbers

**Explorando os Dados:**

Ao mergulhar nos dados, procurei entender padrões e tendências que pudessem ser reveladores para a indústria da aviação, elaborei e resolvei algumas perguntas de negócio para termos mais clareza dos dados contidos na dataset. Utilizei algoritmos de aprendizado de máquina, incluindo Regressão Logística, Random Forest, XGBoost e AdaBoost, para analisar atrasos nos voos. O objetivo era decifrar como esses modelos poderiam impactar as decisões operacionais e melhorar a eficiência do setor.

**Resultados Obtidos:**

Os modelos revelaram insights valiosos sobre os padrões de atraso. O XGBoost, em particular, destacou-se com uma acurácia de 66,58%, uma precisão de 66,43%, um recall de 50,32% e um F1-score de 57,26%. Estas métricas sugerem que o XGBoost pode ser uma escolha sólida para previsões mais precisas em cenários de tráfego aéreo.

Acurácia:

* A acurácia representa a porcentagem geral de previsões corretas feitas pelo modelo. No contexto do XGBoost, atingir uma acurácia de 66,58% significa que aproximadamente dois em cada três casos foram previstos corretamente em relação ao total.

Precisão:

* A precisão mede a proporção de verdadeiros positivos em relação ao total de previsões positivas feitas pelo modelo. No caso do XGBoost, a precisão de 66,43% sugere que, quando o modelo prevê atrasos, ele está correto cerca de dois em cada três vezes.

Recall:

* O recall, também conhecido como sensibilidade ou taxa de verdadeiros positivos, representa a proporção de casos positivos reais que foram corretamente identificados pelo modelo. Para o XGBoost, um recall de 50,32% indica que metade dos casos de atraso real foram capturados pelo modelo.

F1-score:

* O F1-score é a média harmônica entre precisão e recall. Ele fornece uma métrica única que considera tanto os falsos positivos quanto os falsos negativos. O F1-score de 57,26% para o XGBoost sugere um bom equilíbrio entre a precisão e o recall, indicando que o modelo é robusto em identificar atrasos sem comprometer significativamente a precisão.

**Aplicações Práticas:**

Em termos práticos, entender essas métricas pode ser um divisor de águas para a tomada de decisões no setor da aviação. Ao conhecer os padrões de atraso e aplicar modelos preditivos, as companhias aéreas podem otimizar recursos, aprimorar estratégias operacionais e, em última análise, impactar positivamente o resultado financeiro.

**O Valor para o Negócio:**

Ao traduzir esses resultados para o contexto do faturamento anual de $488 bilhões da indústria da aviação, fica evidente que pequenas melhorias na previsão de atrasos podem ter um impacto financeiro significativo. Escolher o modelo certo, como o XGBoost neste caso, pode resultar em uma economia substancial ao reduzir a ocorrência de atrasos.

**Conclusão:**

Navegar pelos céus do tráfego aéreo com base em dados e análises avançadas pode levar a descobertas impactantes. Este estudo demonstra como a compreensão profunda dos padrões de atraso e a aplicação inteligente de modelos preditivos podem gerar valor significativo para a indústria da aviação. O futuro promissor do setor pode muito bem depender da capacidade de decifrar os dados que estão "nas nuvens".

Nota: Os resultados e insights compartilhados aqui são baseados em um conjunto de dados específico e podem variar dependendo das condições e características específicas do setor da aviação. Acredito que o dataset faltaram informações extremamente relevantes para o setor como data e motivo de atraso, porque condições climáticas podem ter mais relação com atrasos em determinadas estações do ano.

---

**Informações do Dataset**

Colunas:

id: Id Único

Airline: Companhia aérea

Flight: Número do voo

AirportFrom: Aeroporto de Saída

AirportTo: Aeroporto de Chegada

DayOfWeek: Dia da Semana

Time: Tempo

Length: O comprimento do terminal do aeroporto

Delay: Atraso (sim ou não)

**Problemas de negócios levantados:**

* Desempenho Geral da Companhia Aérea
* Aeroportos mais Afetados
* Dia da Semana com Maior Número de Atrasos
* Distribuição da Duração dos Atrasos

