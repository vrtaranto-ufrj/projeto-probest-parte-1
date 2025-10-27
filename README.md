# Projeto Probest - Parte 1 (COE241)

Este repositório contém o desenvolvimento da Parte 1 do projeto da disciplina Estatística e Modelos Probabilísticos (COE241).

O objetivo é aplicar a teoria de Estatística, Máxima Verossimilhança (MLE) e Inferência Bayesiana a um conjunto de dados real sobre desempenho de rede (M-Lab NDT).

## Conteúdo do Repositório

* **/script.ipynb**: O notebook Jupyter contendo toda a análise do projeto, seguindo os requisitos do PDF. A análise é dividida em:
    1.  **Fase 1: Análise Exploratória (EDA)** - Carga, tratamento, estatísticas descritivas e visualização gráfica (histogramas, boxplots).
    2.  **Fase 2: Máxima Verossimilhança (MLE)** - Cálculo dos parâmetros $\hat{\theta}_{MLE}$ e avaliação do *fit* dos modelos (Normal para RTT, Gama para Throughput) com gráficos de diagnóstico (QQ-Plots).
    3.  **Fase 3: Inferência Bayesiana** - Definição de priors conjugadas, cálculo da posterior, predição sobre o conjunto de teste e comparação final das estimativas (MLE vs. Bayes).

* **/ndt_tests_corrigido.csv**: O conjunto de dados real (M-Lab NDT) utilizado na análise.

* **/projeto_parte_1.pdf**: O documento com as especificações e requisitos do projeto.