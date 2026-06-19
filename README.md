# machine_learn_0408

Projeto voltado para a **avaliação de modelos de classificação**, com foco na **Matriz de Confusão** e nas métricas de desempenho derivadas dela, aplicadas ao problema de sobrevivência do Titanic.

## Conteúdo

* **titanic.csv**: Conjunto de dados empregado para treinamento e teste do modelo.
* **matriz_de_confusao.ipynb**: Notebook que implementa a lógica de avaliação manualmente. O projeto contempla:
    - **Predição**: Aplicação de pesos ($\\beta$) pré-treinados para gerar previsões em dados de teste.
    - **Matriz de Confusão**: Cálculo manual de Verdadeiros Positivos (VP), Verdadeiros Negativos (VN), Falsos Positivos (FP) e Falsos Negativos (FN).
    - **Métricas de Desempenho**: Implementação das fórmulas matemáticas para:
        - **Acurácia**: Percentual de acertos no total.
        - **Precisão**: Qualidade das predições positivas.
        - **Recall (Sensibilidade)**: Capacidade de detectar a classe positiva.
        - **F1-Score**: Média harmônica entre Precisão e Recall.

## Tecnologias e Bibliotecas

As ferramentas essenciais deste projeto são:

* **Python 3**: Linguagem de programação.
* **NumPy**: Operações matemáticas para cálculo das métricas.
* **CSV**: Manipulação do dataset.
* **Jupyter Notebook**: Ambiente para execução e apresentação dos resultados.

## Como começar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/smokeeaasd/confusion-matrix.git
    ```
2.  Instale o NumPy:
    ```bash
    pip install numpy
    ```
3.  Execute o notebook:
    - Abra o `matriz_de_confusao.ipynb`.
    - Observe a seção de saída para visualizar a matriz detalhada e entender como cada métrica reflete o comportamento do modelo em relação aos sobreviventes e não-sobreviventes.


