# Detecção e Reconhecimento de Placas Veiculares
Este projeto de Trabalho de Conclusão de Curso (TCC) visa explorar e comparar diferentes modelos de detecção de placas veiculares, bem como a aplicação de um modelo de reconhecimento óptico de caracteres (OCR) para extrair informações das placas detectadas.

## Objetivo
O objetivo principal deste projeto é avaliar e comparar o desempenho de três modelos diferentes de detecção de placas veiculares:

- Modelo baseado em YOLO v5.

- Modelo baseado em ResNet Inception v2.

- Modelo de rede neural convolucional (CNN) desenvolvido do zero.

Os resultados desses modelos são comparados em relação à precisão na detecção de placas, utilizando as métricas de precisão e recall. Além disso, uma etapa adicional envolve a aplicação de um modelo de OCR para realizar o reconhecimento de caracteres nas placas detectadas e comparar a precisão do reconhecimento entre os diferentes modelos de detecção.

## Conjunto de Dados
Todos os modelos foram treinados e testados utilizando o mesmo conjunto de dados de placas veiculares. O conjunto de dados pode ser encontrado [Aqui](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection).

## Estrutura do Projeto
O projeto está organizado da seguinte forma:

- yolov5: Contém o código e os arquivos necessários para treinar e usar o modelo baseado em YOLO v5.
- inception-resnet-v2: Contém o código e os arquivos necessários para treinar e usar o modelo baseado em ResNet Inception v2.
- scratch: Contém o código e os arquivos necessários para treinar e usar o modelo de CNN desenvolvido do zero.
- ocr: Contém o notebook utilizado para avaliar o desempenho dos modelos de detecção com o modelo de OCR.

## Resultados
Os resultados obtidos durante o treinamento e teste dos modelos estão disponíveis nos respectivos diretórios. Além disso, os resultados da comparação entre os modelos de detecção e o desempenho do OCR estão detalhados no notebook ocr.

## Observações
Todo o projeto foi realizado utilizando as seguintes configurações
- SO: Ubuntu 23.04
- CPU: Intel(R) Core(TM) i5-9400 CPU @ 2.90GHz
- MEM: 16GB
- GPU: RTX 3060
- CUDA: Release 11.8, V11.8.89
- Python: 3.10

## Conclusão
Este projeto fornece uma análise comparativa abrangente de diferentes abordagens para a detecção e reconhecimento de placas veiculares. Os resultados obtidos podem ser úteis para orientar a escolha do melhor modelo para aplicações específicas e fornecer insights para futuras pesquisas nesta área.