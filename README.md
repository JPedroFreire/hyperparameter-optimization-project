# Projeto de Computação Evolutiva

Este é o projeto implementado na cadeira de Computação Evolutiva. É um algoritmo evolucionário baseado no artigo [Genetic Algorithm based hyper-parameters optimization for transfer Convolutional Neural Network](https://arxiv.org/abs/2103.03875). O projeto utiliza a biblioteca [DEAP](https://deap.readthedocs.io/en/master/) para implementar um algoritmo genético que modifica as camadas treináveis de um modelo CNN baseado no [MobileNetV2](https://arxiv.org/abs/1801.04381). O dataset utilizado para treinar os modelos de CNN foi uma versão reduzida do [AIRTLab](https://www.sciencedirect.com/science/article/pii/S2352340920314682), dataset desenvolvido para treinar modelos para a detecção automática de violência em vídeo.


## Execução

### Versão Python utilizada: **_Python 3.11.x_**

Para instalar as bibliotecas necessárias, executar o comando:

```console
$ pip install -r requirements.txt
```

## Resultados
Abaixo estão gráficos de resultados obtidos com o experimento:

* Fitness médio
<img src="https://github.com/mrjohnnus/evolutionary-computation-project/blob/main/Resultados/avg.png"/>

* Fitness máximo
<img src="https://github.com/mrjohnnus/evolutionary-computation-project/blob/main/Resultados/max.png"/>

* Fitness mínimo
<img src="https://github.com/mrjohnnus/evolutionary-computation-project/blob/main/Resultados/min.png"/>
  
* Desvio padrão
<img src="https://github.com/mrjohnnus/evolutionary-computation-project/blob/main/Resultados/std.png"/>
  
