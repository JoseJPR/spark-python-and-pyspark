![Python Logo](./assets/logo-python.png)
![Spark Logo](./assets/logo-spark.png)

# Spark with Python and PySpark (WIP)

## Curso

Curso vinculado a los ejemplos de este repositorio: https://cursos.datademia.es/p/p-spark-y-python-con-pyspark

## Prepare Environment

### 1. Install Scala

```bash
brew install scala
```

### 2. Install Apache Spark

```bash
brew install apache-spark
```

### 3. Install PySpark

```bash
pip install pyspark
```

### 4. Add Environment Variables
```
export PYSPARK_PYTHON=/Users/user_name/.pyenv/shims/python
export PYSPARK_DRIVER_PYTHON=/Users/user_name/.pyenv/shims/python
```

### 5. Run Jupiter Notebook
```bash
jupyter notebook
``` 

## Links of interest

- More info about Anaconda: https://www.anaconda.com/download
- More info about Apache Spark: https://spark.apache.org/downloads.html
- Jupyter Notebooks in VS Code: https://code.visualstudio.com/docs/datascience/jupyter-notebooks
- Spark RDD APIs: https://spark.apache.org/docs/latest/api/python/reference/pyspark.html#rdd-apis