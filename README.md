# **ANÁLISE COMPARATIVA DE MODELOS DE APRENDIZADO DE MÁQUINA NA DETECÇÃO DE DIABETES EM ESTÁGIO INICIAL**
## **Resumo do projeto**
Diabetes é uma doença que atinge a humanidade de maneira global sendo
uma das doenças com mais casos nos últimos anos. Em casos de diagnósticos tardios,
juntamente com a falta do correto tratamento, a doença pode apresentar riscos à saúde devido
às possíveis complicações micro e macro vasculares. Com o intuito de realizar o diagnóstico
prévio da Diabetes, este estudo utiliza algoritmos de Machine Learning, a partir de um
conjunto de dados com atributos de sintomas, como sede excessiva, fraqueza e retardo da
cicatrização, evitando a necessidade da realização de exames específicos. Para isso, os
modelos avaliados foram Random Forest, XGBoost, Support Vector Machine e Naive Bayes.
Para análise dos resultados, métricas como Precision, Recall, Accuracy, F1-Score e Balanced
Accuracy foram utilizadas.
## **Dataset**
Foi utilizado um conjunto de dados público, disponível na UCI Machine Learning Repository
## **Pré-processamentos realizados**
- Conversão dos valores categóricos para numéricos;
- Normalização dos dados numéricos -> Para evitar que o modelo desse mais importância para um dos atributos do que para os demais;
- Balanceamento dos dados -> Para evitar que o modelo desse a mesma importância para ambas as classes;
## **Sobre os algoritmos**
Os algoritmos utilizados foram selecionados com base no levantamento bibliográfico realizado em artigos que fizeram experimentos com o mesmo foco
## **Resultado**
Random Forest foi o mais eficaz em todos as métricas e o XGboost ficou em segundo lugar.  
Uma das hipóteses para esse resultado é pelo dataset ter quase todos atributos categóricos.
## **Próximos passos**
- Obter mais dados de diferentes regiões;
- Realizar testes junto de especialistas da saúde para validar a aplicabilidade do modelo em cenários práticos;
## **Conclusão**
Ter um algoritmo em produção, que leva em consideração os atributos do dataset utilizado permitirá o diagnóstico prévio para todas as classes da sociedade, por levar em consideração sintomas e percepções do próprio paciente, sem a necessidade de exames prévios.
