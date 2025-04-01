## 1. Como Você Definiria o aprendizado de máquina?
O Aprendizado de máquina é um algortimo que analisa dados e usa para iniciar uma 
tarefa que normalmente de inteligência humana.

## 2. Você Consegue apontar quatro tipos de problemas que se destacam?
 - Mau dados
 - Mau Modelo de aprendizado
 - Mau parâmetros de ensino
 - Mau algoritimo para o problema a ser tratado

## 3. O que é um conjunto de treinamento Rotulado?
Usado na aprendizagem supervisonada, no qual o conjunto de dados de treinamento possui já são rotulados, logo é possível treinar o modelo de aprendizado para que incie a tarefa conforme o conjunto de dados.

## 4. Quais são as duas tarefas supervisionadas mais comum?
- Regressão
- Classificação

## 5. Você consegue citar quatros tarefas comuns não supervisionadas?
- Agrupamento em _Clusters_ (Clustering)
- Aprendizado de Regras de Associação
- Densidade de Probabilidade (Análise de Anomalias)
- Redução de Dimensionalidade 

## 6. Qual Tipo de algoritimo de aprendizado de máquinas você usaria para possibilitar que um robô andasse por aí em lugares inexplorados?
Um algoritmo de aprendizado de máquinas supervisionado, pois eu posso treinar o robô em terrenos conhecidos e assim ele possa andar por lugares inexplorados.

## 7. Que Tipo de Algoritimo você utilizaria a fim de segmentar seus clientes em diversos grupos?
O alogoritimo de aprendizado não supervisionado no tipo Clustering, pois ele irá agrupar os clientes em grupos.

## 8. Você acha que o problema de detecção de spam tem a ver com o aprendizado supervisionado ou não supervisionado?
Supervisionado, pois o algoritmo deve ser treinado com uma base de dados de emails rotulados como spam ou não spam.

## 9. O que é um sistema de aprendizado online?
Aprende de forma adaptiva, com dados em tempo real, mas pode ter um desempenho ruim em dados antigos ou novos foram adicionados.

## 10. O que é aprendizado out-of-core?
Algoritimos de AM que podem lidar com grandes quantidades que não cabem na memória do computador.

## 11. Que Tipo de algoritimo de aprendizado depende de uma medida de similaridade para efetuar predições?
K-Nearest Neighbors (KNN)

## 12. Qual a diferença entre um parâmetro de modelo e o hiperparâmetro de algoritimo de aprendizado?
- **Parametro de modelo**: São os parâmetros que são ajustados durante o treinamento do modelo.
- **Hiperparâmetro de algoritimo de aprendizado**: São os parâmetros que são ajustados antes do treinamento do modelo.

## 13. Para que servem os algoritimos de aprendizado baseados em modelos? Qual é estratégia mais comum que eles utilizam para serem bem-sucedidos? Como eles fazem predições?
 - Algoritimos que generalizam através um modelo baseado no cojunto de dados.
 - A estratégia mais comum ajuste do modelo com base em dados rotulados e e geneeralização do modelo com base em dados não rotulados.
 - Através do processo de inferênciam, no qual o modelo é treinado com dados rotulados e então usado para fazer previsões em dados não rotulados.

## 14. Você pode mencionar quatro dos principais desafios do aprendizado de maquina?
- Dados de treinamento de baixa qualidade
- Métodos de treinamento incorretos
- Introdução de vieses implícitos
- Generalização excessiva

## 15. Como o modelo tenha um bom desepenho nos dados de treinamento, mas a generalização deixa a desejar em instâncias novas, o que está acontecendo? Você pode exemplificar três possiveis soluções?
- **Problema 1**: O modelo está sendo treinado demais.
- **Problema 2**: O modelo possui muito ruido nos dados de treinamento.
- **Problema 3**: O modelo está está muito flexível a entrada de novos dados.

- **Solução 1**: (Regularização L1 e L2): Adiciona penalidades para reduzir a complexidade do modelo e evitar o ajuste excessivo aos dados de treinamento.
- **Solução 2**: (Validação Cruzada) Avalia o modelo em diferentes subconjuntos de dados para garantir que ele generalize bem para dados não vistos.
- **Solução 3**: (Ajuste de Parâmetros) Ajusta os parâmetros do modelo para encontrar o melhor equilíbrio entre ajuste aos dados de treinamento e generalização.
- **Solução 4**: (_Early Stopping_) Interrompe o treinamento antes que o modelo comece a ajustar-se excessivamente aos dados de treinamento.

## 16. O que é um conjunto de testes e por que você o utilizaria?
Um conjunto de testes é um conjunto de dados que é usado para avaliar o desempenho de um modelo de aprendizado de máquina. Ele é usado para avaliar o desempenho do modelo em dados que não foram usados para treinar o modelo.
## 17. Qual é o propósito de um cojunto de validação?
O conjunto de validação é usado para ajustar os hiperparâmetros do modelo de aprendizado de máquina. Ele é usado para escolher os melhores hiperparâmetros para o modelo.
## 18. O que é um train-dev-set, quando é necessário e como usá-lo?
Um train-dev-set é um conjunto de dados que é usado para ajustar os hiperparâmetros do modelo de aprendizado de máquina. Ele é usado para escolher os melhores hiperparâmetros para o modelo.
## 19. O que pode sair de errado se você ajustar os hiperparâmetros utilizando o conjunto de teste?
Se você ajustar os hiperparâmetros utilizando o conjunto de teste, você pode acabar com um modelo que se ajusta muito bem aos dados de teste, mas não generaliza bem para dados novos.