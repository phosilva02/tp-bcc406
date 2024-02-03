# Utilização de Redes Neurais para diagnóstico de COVID-19

Implementação do trabalho prático da disciplina BCC406, do período 23.2, cujo nome é "Utilização de Redes Neurais para diagnóstico de COVID-19" e cujo autores são Caio Monteiro de Oliveira e Pedro Henrique Oliveira da Silva.

Devido a restrições de hardware, os experimentos foram feitos no kaggle e estão disponíveis por este link: "https://www.kaggle.com/phosilva/tp-bcc406".

## Overview

Este trabalho investiga o papel crucial dos exames de raios-X no diagnóstico e na avaliação da gravidade da infecção por Covid-19. Ele se concentra em comparar o desempenho de diferentes Redes Neurais Convolucionais (CNNs) na classificação de imagens de raio-X de tórax para o diagnóstico da Covid-19 em pacientes. As CNNs EfficientNet, ResNet e DenseNet foram utilizadas para este fim. Os resultados revelaram desempenhos razoáveis, com destaque para as arquiteturas ResNet e DenseNet, que apresentaram desempenho particularmente bom.

## Experimentos e resultados

a Figura abaixo proporciona uma representação visual dos resultados, exibindo um gráfico de barras que destaca as diferenças de desempenho entre os modelos. Ao observar a imagem, é evidente que a EfficientNet apresentou um desempenho inferior em comparação com as ResNet e DenseNet, enquanto estas duas últimas obtiveram resultados semelhantes. Esta observação sugere que as arquiteturas ResNet e DenseNet possuem vantagens significativas em relação à EfficientNet para a tarefa de classificação de imagens de raios-X. Apesar das variações de desempenho entre os folds e entre os modelos, nenhum dos valores de acurácia obtidos foi menor que 66,7\%. Esse resultado sugere que, de maneira geral, todas as redes apresentaram um desempenho razoável na tarefa de classificação de imagens de raios-X.


