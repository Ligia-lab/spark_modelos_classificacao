# 🔥 Spark Modelos de Classificação

Este repositório contém experimentos e implementações de modelos de classificação utilizando o Apache Spark (PySpark). O objetivo é aplicar diferentes algoritmos de machine learning para resolver problemas de classificação em larga escala com foco em performance e escalabilidade.

## 📂 Estrutura do Projeto

```
spark_modelos_classificacao

├── dados

├── notebook

└── README.md 
```

## ⚙️ Tecnologias Utilizadas

- Python 3
- Apache Spark (PySpark)
- Pandas / NumPy
- MLlib (Spark ML)
- Jupyter Notebooks

## 📌 Modelos Implementados

- Regressão Logística (`LogisticRegression`)
- Árvore de Decisão (`DecisionTreeClassifier`)
- Random Forest (`RandomForestClassifier`)

Todos os modelos são treinados utilizando o módulo `pyspark.ml` com pipelines de transformação (feature engineering, encoding, normalização, etc).

## 🚀 Como Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/Ligia-lab/spark_modelos_classificacao.git
cd spark_modelos_classificacao
```

### 2. Criar ambiente virtual e instalar dependências

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Iniciar um notebook

```bash
jupyter notebook
```


## 📊 Avaliação

Os modelos são avaliados com métricas clássicas de classificação:

* Accuracy
* Precision / Recall
* F1-Score
* Matriz de confusão

## 🧪 Exemplos

Você pode acessar os notebooks na pasta `/notebooks` para visualizar exemplos de experimentação com diferentes modelos e bases de dados.

## 📎 Referências

* [Apache Spark MLlib](https://spark.apache.org/mllib/)
* [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/)

