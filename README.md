# Relatórios de Aulas Práticas — Linguagem de Programação

Este repositório reúne quatro notebooks Jupyter (`.ipynb`) com atividades práticas da disciplina de Linguagem de Programação. Os exercícios usam Python para trabalhar conceitos de programação e aplicações de análise de dados.

## Conteúdo

| Arquivo | Tema | O que é praticado |
| --- | --- | --- |
| `Unidade 01 - RAP.ipynb` | Sistema de gestão de notas | Funções, listas, laços de repetição, tratamento de entradas inválidas, cálculo de média e classificação do aluno (aprovado ou reprovado). |
| `Unidade 02 - RAP.ipynb` | Sistema de gerenciamento de biblioteca | Classes e objetos, cadastro, listagem, busca e remoção de livros, controle de estoque e gráfico de exemplares por gênero. |
| `Unidade 03 - RAP.ipynb` | Análise de vendas de varejo | Criação e consulta de banco SQLite, preparação e análise dos dados com Pandas e visualizações com Matplotlib e Seaborn. O notebook apresenta uma versão inicial e outra ampliada, com análises por categoria, período e produto. |
| `Unidade 04 - RAP.ipynb` | Classificação do conjunto Iris | Pré-processamento e normalização de dados, divisão entre treino e teste, construção e avaliação de uma rede neural com TensorFlow/Keras e análise de previsões. |

## Tecnologias utilizadas

- Python 3 e Jupyter Notebook (os arquivos também podem ser abertos no Google Colab).
- Unidade 02: Matplotlib.
- Unidade 03: SQLite (módulo `sqlite3`, incluído no Python), Pandas, Matplotlib e Seaborn.
- Unidade 04: TensorFlow/Keras, Pandas, scikit-learn e NumPy.

As bibliotecas externas precisam estar instaladas no ambiente usado para executar cada notebook. A Unidade 01 não requer bibliotecas externas.

## Como executar

1. Abra o arquivo `.ipynb` desejado no Jupyter Notebook, JupyterLab ou Google Colab.
2. Instale as dependências externas indicadas acima, caso ainda não estejam disponíveis.
3. Execute as células na ordem em que aparecem.

Na Unidade 01, o programa solicita dados pelo terminal; em ambientes de notebook, responda às solicitações de entrada apresentadas durante a execução. A Unidade 03 cria o banco `dados_vendas.db` no diretório de execução e, na versão ampliada, salva gráficos em arquivos PNG. A Unidade 04 salva `historico_treino.json` e `matriz_confusao.npy` ao final da análise complementar.

## Objetivo

Os relatórios documentam a aplicação gradual de conceitos da disciplina: estruturas básicas e funções, programação orientada a objetos, persistência e exploração de dados, visualização e introdução a aprendizado de máquina.
