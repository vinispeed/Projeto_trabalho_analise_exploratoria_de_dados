# Trabalho de Análise Exploratória de Dados - Titanic

## Visão Geral

Este projeto tem como objetivo realizar uma análise exploratória do conjunto de dados do Titanic, disponível no Kaggle (https://www.kaggle.com/c/titanic). O objetivo principal é compreender melhor as informações presentes na base de treino e extrair insights sobre os tipos de pessoas que tinham maior probabilidade de sobreviver ao naufrágio.

Embora o problema gerador seja a criação de um modelo preditivo para determinar a probabilidade de sobrevivência, o foco inicial deste trabalho é a exploração detalhada dos dados.

## Dicionário de Dados

| Variável    | Definição                                  | Chave                     |
|-------------|--------------------------------------------|---------------------------|
| survived    | Sobrevivência                              | 0 = Não, 1 = Sim          |
| pclass      | Classe de ingresso                         | 1 = 1º, 2 = 2º, 3 = 3º      |
| name        | Nome                                       |                           |
| sex         | Sexo                                       |                           |
| age         | Idade em anos                              |                           |
| sibsp       | Número de irmãos/cônjuges a bordo do Titanic |                           |
| parch       | Número de pais/crianças a bordo do Titanic  |                           |
| ticket      | Número do bilhete                          |                           |
| fare        | Tarifa de passageiro                       |                           |
| cabin       | Número da cabine                           |                           |
| embarked    | Porto de embarque                          | C = Cherbourg, Q = Queenstown, S = Southampton |

## Estrutura do Projeto

O projeto consiste em um notebook Jupyter (`.ipynb`) contendo o código Python para a análise exploratória dos dados. A estrutura atual é a seguinte:

1.  **Carregar e Explorar o Conjunto de Dados:**
    * Importação das bibliotecas necessárias (Pandas, NumPy, Matplotlib, Seaborn).
    * Carregamento da base de dados de treino (`train.csv`).
    * Compreensão do conjunto de dados e suas variáveis, incluindo a identificação dos tipos de variáveis (numéricas e categóricas).

## Como Executar o Código

1.  **Pré-requisitos:**
    * Python 3 instalado.
    * As seguintes bibliotecas Python devem estar instaladas:
        * Pandas (`pip install pandas`)
        * NumPy (`pip install numpy`)
        * Matplotlib (`pip install matplotlib`)
        * Seaborn (`pip install seaborn`)
    * O arquivo `train.csv` deve estar presente no mesmo diretório do notebook ou o caminho para o arquivo deve ser atualizado no código.

2.  **Execução:**
    * Abra o notebook Jupyter (`.ipynb`) em um ambiente Jupyter (Jupyter Notebook, JupyterLab ou Google Colab).
    * Execute as células de código sequencialmente para realizar a análise exploratória dos dados.

## Próximos Passos (Análise Exploratória Contínua)

As próximas etapas da análise exploratória incluirão:

* **Estatísticas Descritivas:** Calcular e analisar medidas de tendência central, dispersão e forma para as variáveis numéricas.
* **Análise de Valores Faltantes:** Identificar e tratar valores ausentes em diferentes colunas.
* **Análise Univariada:** Explorar a distribuição de cada variável individualmente através de histogramas, gráficos de barras, boxplots, etc.
* **Análise Bivariada e Multivariada:** Investigar as relações entre pares e grupos de variáveis, com foco na variável alvo (`Survived`). Isso pode envolver o uso de gráficos de dispersão, boxplots agrupados, tabelas de contingência e mapas de calor.
* **Identificação de Outliers:** Detectar e analisar valores atípicos nas variáveis numéricas.
* **Engenharia de Features (Inicial):** Considerar a criação de novas variáveis a partir das existentes que possam ser relevantes para a análise (por exemplo, tamanho da família).

## Contribuição

Este é um projeto individual para fins de aprendizado e análise exploratória. Contribuições externas não são esperadas neste momento.

## Autor

Marcos Vinicius da Silva
