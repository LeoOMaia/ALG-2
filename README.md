# To do
1. [ ] separar os dados em conjuntos, deverão ser divididos em dois: um subconjunto com 70%
das amostras que será usado para o ajuste do modelo (treinamento), e um outro de
30% usado para avaliar o desempenho do modelo na tarefa de classificação (mensurar
a taxa de acertos com dados desconhecidos). Deverão ser computadas as métricas:
precisão, revocação e f1-escore.

2. [v] implementar o algoritmo graham scan para encontrar o fecho convexo dos grupos.

3. [v] implementar o algoritmo de varredura para encontrar o fecho convexo dos grupos se existir, deverá ser verificado se há ou não sobreposição dessas classes/envoltórias através do algoritmo de varredura linear para verificação de interseção de segmentos. Caso não haja interseção entre segmentos de envoltórias
distintas, então os dados são linearmente separáveis.O algoritmo deve encontrar os pontos mais próximos
entre as duas envoltórias. O modelo a ser reportado será a reta perpendicular ao
segmento que une esses dois pontos e que passa sobre seu ponto médio.

4. [v] implementar um algoritmo que recebe o 30% restante de amostra e classifica para um grupo de acordo com sua posicao, o modelo atribui o mesmo rótulo a uma nova amostra que os pontos da envoltória que se localizam na mesma região. Isto é, se um ponto estiver abaixo/à esquerda da reta gerada pelo modelo, então ele receberá o
mesmo rótulo que os pontos da envoltória dessa região.

5. [v] avaliar para qual grupo foi designado a amostra e comparar com o rótulo real, computando a taxa de acerto.

6. [ ] documentar.