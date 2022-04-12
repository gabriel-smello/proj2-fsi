# Repositório para o projeto individual 2 da matéria de Fundamentos de Sistemas Inteligentes
 
Link Colab: https://colab.research.google.com/drive/1gcDRnrJAjNq6lIYLBxEa3-IjYja_SHSd?usp=sharing

A classificação de insetos prejudiciais em plantações comerciais é uma necessidade, visto que as
técnicas de manejo a serem aplicadas dependerão dessa correta classificação.

Em
https://data.mendeley.com/datasets/s62zm6djd2/1
encontra-se disponível um banco de imagens de oito (8) pragas comuns em plantações de tomate.

Há 609 imagens originais, no total, das 8 pragas em um diretório, e também 4263 imagens após
técnicas de augmentation já aplicadas.

Este projeto pede o seguinte: (utilizando as 4263 imagens)
Escrever um projeto Keras/TensorFlow, que rode em colab/Google jupyter, e aplique uma rede
CNN ResNet-18, com transferência de aprendizagem, e gere uma classificação final das 8 pragas.
(5,0 ptos)

Avaliações extras:
1. Métricas de acurácia, revocação e f1 em todas as classes; (2,0 ptos)
2. Pequeno relatório/texto indicando resultados de sucesso e potenciais melhorias futuras; (3,0 ptos)


## Fontes
https://stackoverflow.com/questions/39770376/scikit-learn-get-accuracy-scores-for-each-class \
https://chroniclesofai.com/transfer-learning-with-keras-resnet-50/ \
https://stackoverflow.com/questions/45930750/how-to-output-per-class-accuracy-in-keras
