# Projeto Fluxo

## Descrição

O **Projeto Fluxo** é um projeto de clusterização de clientes da empresa júnior Fluxo Consultoria. Por meio de algoritmos de machine learning, nós temos como objetivo auxiliar a empresa a entender melhor o perfil de seus clientes a fim de desenvolver uma estratégia de marketing, prospecção e negociação mais adequada para a conversão de seus leads. 

## Integrantes

- **Eduardo Batista** - Engenharia de Produção, Universidade de Brasília  
  [LinkedIn](https://www.linkedin.com/in/eduardo-luiz-dias-batista-90b8a51b3/) | [GitHub](https://github.com/EduardoLDB2001)

- **Fábio Parra** - Computação, Universidade de Brasília  
  [LinkedIn](https://www.linkedin.com/in/flbparra/) | [GitHub](https://github.com/flbparra)

- **Pedro Fernandes** - Computação, Universidade de Brasília  
  [LinkedIn](https://www.linkedin.com/in/pedrofernandss) | [GitHub](https://github.com/pedrofernandss)

## Tecnologias Utilizadas

- **Python**
- **Jupyter Notebook**

## Estrutura do Projeto

Abaixo está a organização dos diretórios e arquivos principais deste projeto:

`
root/
│
├── data/                  # Armazena os datasets
│   ├── raw/               # Armazena os dados brutos não processados
│   └── processed/         # Armazena os dados processados, prontos para uso
│
├── notebooks/             # Notebooks Jupyter utilizados para análise exploratória         
│
├── src/                   # Código-fonte do projeto
│   ├── clustering/        # Algoritmos de clusterização
│   ├── preprocessing/     # Scripts de pré-processamento dos dados
│   ├── utils/             # Funções utilitárias
│   └── main.py            # Arquivo principal para executar a pipeline de clusterização
│
├── models/                # Modelos treinados ou checkpoints
│
├── tests/                 # Scripts de testes para validar o código
│   └── test_clustering.py # Exemplo de teste unitário
│
├── reports/               # Relatórios de resultados, gráficos, e insights
│
├── requirements.txt       # Arquivo com as dependências do projeto (pacotes Python)
├── README.md              # Instruções e documentação do projeto
├── .gitignore             # Arquivos e pastas a serem ignorados pelo Git
`