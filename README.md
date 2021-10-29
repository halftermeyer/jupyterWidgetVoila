# jupyterWidgetVoila

Create a **dashboard** with **jupyter widgets** and **voilà**

The notebook connects to Movie Graph Neo4j database.

From Neo4j desktop...

```cypher
:play movie-graph
```

...and load the data.

Edit connection data in the notebook.

```python
uri = "neo4j://localhost:7687"
driver = GraphDatabase.driver(uri, auth=("user", "password"))
```

## install libs

```terminal
pip install ipywidget
pip install voila
```

## run dashboard

```terminal
voila dashboard.ipynb
```
