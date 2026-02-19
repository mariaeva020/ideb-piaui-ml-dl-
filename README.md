# ideb-piaui-ml-dl

Modelagem preditiva do IDEB municipal do estado do Piauí utilizando algoritmos de Machine Learning (ML) e Deep Learning (DL).

## 1. Descrição

Este repositório contém os scripts, notebook e base de dados utilizados no estudo que investiga a predição do Índice de Desenvolvimento da Educação Básica (IDEB) nos anos iniciais do ensino fundamental, em nível municipal, no estado do Piauí.

Foram avaliados modelos lineares, métodos baseados em árvores, ensembles e arquiteturas de redes neurais profundas, com validação cruzada k-fold e análise comparativa de desempenho.

## 2. Estrutura do Repositório

ideb-piaui-ml-dl/
│
├── dados/
│ └── base_anos_iniciais.xlsx
│
├── cadernos/
│ └── ideb_modelagem.ipynb
│
├── README.md
├── LICENSE
└── requirements.txt

## 3. Requisitos

Python 3.10+

Principais bibliotecas:

- pandas
- numpy
- scikit-learn
- xgboost
- tensorflow
- keras
- matplotlib
- seaborn
- shap
- boruta

Para instalar as dependências:

```bash
pip install -r requirements.txt



4. Execução

Clone o repositório:

git clone https://github.com/mariaeva020/ideb-piaui-ml-dl.git


Acesse o diretório:

cd ideb-piaui-ml-dl


Execute o notebook localizado em:

cadernos/ideb_modelagem.ipynb


Certifique-se de manter a estrutura de pastas para que o caminho relativo da base de dados funcione corretamente:

caminho_arquivo = "dados/base_anos_iniciais.xlsx"

5. Reprodutibilidade

Os experimentos foram conduzidos com divisão treino-teste (70/30) e validação cruzada k-fold (k=5). As versões das bibliotecas utilizadas estão especificadas no arquivo requirements.txt.

6. Referência

Caso utilize este material, cite:

CASTRO SILVA, Maria Eva Clemencia Fonseca de. Modelagem preditiva do IDEB municipal no estado do Piauí utilizando Machine Learning e Deep Learning. 2025.


