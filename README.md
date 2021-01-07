# AOD

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/AOD-brightgreen.svg" alt="AOD">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Anomaly-Detection-blue.svg" alt="Anomaly-Detection">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Outlier-Detection-orange.svg" alt="Outlier-Detection">
  </a>
</p>

O principal objetivo deste repositório é fazer a organização dos resultados obtidos pelo método de Anomaly and Outlier Detection (AOD) que realiza a detecção em dados de séries temporais. 

A pasta [[Instances](./Instances/)] armazena os arquivos de instância em csv utilizados nos experimentos. 

A pasta [[Results](./Results/)] armazena os resultados obtidos pelo método AOD. Este diretório, por sua vez, possui as seguintes subpastas: 1-YOB, 2-NAB, 3-Synthetic-Dataset e 4-Case-Study. 

## Results YOB

A pasta [[1-YOB](./Results/1-YOB)] possui quatro subpastas que são: A1, A2, A3 e A4. Dentro de cada uma dessas pastas temos as imagens mostrando os resultados dos experimentos. Algumas das imagens dos experimentos são como mostrado a seguir. 

| Results - Benchmark A1, A3                             | Results - Benchmark A2, A4                             |
|:------------------------------------------------------:|:------------------------------------------------------:|
| ![](./Results/1-YOB/A1/plot-real_55.csv.svg)           | ![](./Results/1-YOB/A2/plot-synthetic_38.csv.svg)      |
| A1 Benchmark - Instance 55                             | A2 Benchmark - Instance 38                             |
| ![](./Results/1-YOB/A3/plot-A3Benchmark-TS39.csv.svg)  | ![](./Results/1-YOB/A4/plot-A4Benchmark-TS35.csv.svg)  |
| A3 Benchmark - Instance 39                             | A4 Benchmark - Instance 35                             |

## Results NAB

Na pasta [[NAB](./NAB/)] temos os resultados do método AD3C aplicado sobre o benchmark do Numenta Anomaly Benchmark.

## Results Synthetic Dataset


## Results Case Study

Na pasta [[Casy-Study](./Casy-Study/)] temos os resultados do método AD3C aplicado sobre um estudo de caso real. A pasta estudo de caso possui quatro subpastas, que são: analysis-training-fraction, analysis-window-size, analysis-cut-factor e analysis-statistical-features. Dentro de cada uma dessas pastas existem ainda mais subpastas com nomes que revelam os valores dos parâmetros utilizados nos experimentos de análise de sensibilidade. Por fim, dentro de cada pasta temos imagens com os resultados dos experimentos. Um exemplo de imagem de um dos experimentos são como mostrado a seguir. 

![](./Case-Study/analysis-fraction-train/outliers_nonstationary_0.1sens_0.1margin_60wsize_0.4fractiontrain/plot-result.svg)
