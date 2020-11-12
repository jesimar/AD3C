# AD3C

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/AD3C-brightgreen.svg" alt="AD3C">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Anomaly-Detection-blue.svg" alt="Anomaly-Detection">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Outlier-Detection-orange.svg" alt="Outlier-Detection">
  </a>
</p>

Repositório com os resultados do método AD3C. 

Na pasta [[YOB](./YOB/)] temos os resultados do método AD3C aplicado sobre o benchmark do Yahoo Outlier Benchmark. A pasta YOB possui quatro subpastas que são: A1, A2, A3 e A4. Dentro de cada uma dessas pastas, existem ainda três subpastas, que são: analysis-training-fraction, analysis-window-size e analysis-cut-factor. Dentro de cada uma dessas pastas existem ainda mais subpastas com nomes que revelam os valores dos parâmetros utilizados nos experimentos de análise de sensibilidade. Por fim, dentro de cada pasta temos imagens com os resultados dos experimentos. 

| Results                                                                 |
|-----------------------------------|-------------------------------------|
| ![](./YOB/A1/analysis-training-fraction/A1-full_outliers_nonstationary_0.1sens_0.1margin_10wsize_0.4fractiontrain/plot54.svg)  | ![](./YOB/A2/analysis-training-fraction/A2-full_outliers_nonstationary_0.1sens_0.1margin_10wsize_0.4fractiontrain/plot37.svg)  |
| A1 Benchmark - Instance 55 | A2 Benchmark - Instance 38 |
| ![](./YOB/A3/analysis-training-fraction/A3-full_outliers_nonstationary_0.1sens_0.1margin_10wsize_0.4fractiontrain/plot38.svg)  | ![](./YOB/A4/analysis-training-fraction/A4-full_outliers_nonstationary_0.1sens_0.1margin_10wsize_0.4fractiontrain/plot34.svg)  |
| A3 Benchmark - Instance 39 | A4 Benchmark - Instance 35 |

Na pasta [[NAB](./NAB/)] temos os resultados do método AD3C aplicado sobre o benchmark do Numenta Anomaly Benchmark.


Na pasta [[Casy-Study](./Casy-Study/)] temos os resultados do método AD3C aplicado sobre um estudo de caso real.

![](./Case-Study/analysis-fraction-train/outliers_nonstationary_0.1sens_0.1margin_60wsize_0.4fractiontrain/plot-result.svg)
