Predict_Titanic
==============================

Esse projeto tem intuito com os dados anteriores do Titanic, quais passageiros sobreviveriam ao Titanic, foram testados duas formas de tratamento de dados, a primeira, no arquivo desenvolvimento.py, onde utilize o pipeline de dados para realizar o tratamento e a segunda desenvolvimento_2.py, que quebrei o pipeline em duas etapas (Enconding e Normalização).
Com as analises das metricas de acuracia e curva ROC-AUC, cheguei a conclusão que o modelo mais estavel e com boas metricas com o modelo do arquivo desenvolvimento_2.py que tem o Grid e Random Forest como sua "base".

Caso tenha alguma dica para alteração no modelo, podemos estar debatendo.

Obrigado pelo apoio.

Vamos para mais uma metaaa.

![alt text](image.png)

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    │
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │   
    │   
    │  
    │       
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
