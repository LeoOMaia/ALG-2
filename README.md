# Análise de Dados com Geometria Computacional

## Introdução

Este projeto tem como objetivo analisar 10 conjuntos de dados diferentes usando algoritmos de Geometria Computacional. As técnicas usadas neste projeto visam descobrir insights interessantes e padrões nos dados, além de realizar comparações entre os conjuntos de dados.

## Conjuntos usados

Foram usados os seguintes conjuntos para serem analisados, 5 deles apresentam interseções e os outros 5 não apresentam.

- banana.dat
- haberman.dat
- ionosphere.dat
- iris.dat
- led7digital.dat
- letter.dat
- newthyroid.dat
- texture.dat
- wine.dat
- zoo.dat

## Uso de Graham Scan para achar o envoltório convexo

O algoritmo de Graham Scan é utilizado em problemas que envolvem a identificação de convex hulls. Esse algoritmo é eficiente e tem uma complexidade de tempo de O(n * log(n)), onde n é o número de pontos no conjunto.

![Exemplo de Imagem](https://github.com/LeoOMaia/ALG-2/blob/main/convex_hull.png)

![Exemplo de Imagem](https://github.com/LeoOMaia/ALG-2/blob/main/convex_hull_code.png)

## Achar os pontos mais próximos entre dois convex hulls

O algoritmo roda em O(n^2) e verifica para cada ponto dos convex hulls quais estão mais pertos.

![Exemplo de Imagem](https://github.com/LeoOMaia/ALG-2/blob/main/closest_points.png)

![Exemplo de Imagem](https://github.com/LeoOMaia/ALG-2/blob/main/closest_points_code.png)

## Reta Perpendicular a aresta formada entre pontos proximos

Essa função é responsável por calcular os pontos que formam uma reta perpendicular. Ela utiliza um método simples para encontrar a reta perpendicular aos dois pontos fornecidos e retorna os pontos que a compõem  O(1).

![Exemplo de Imagem](https://github.com/LeoOMaia/ALG-2/blob/main/perpendicular.png)

![Exemplo de Imagem](https://github.com/LeoOMaia/ALG-2/blob/main/perpendicular_code.png)

## Estatítiscas de teste

Esses testes medem a proporção de verdadeiros positivos (acertos) em relação ao total de positivos previstos, o *recall* mede a proporção de verdadeiros positivos em relação ao total de positivos reais. O *F1-score* mede o equilíbrio entre precisão e recall, levando em consideração ambos os valores.

![Exemplo de Imagem](https://github.com/LeoOMaia/ALG-2/blob/main/est.png)


