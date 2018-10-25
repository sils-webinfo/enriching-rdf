Create a Python 3 virtual environment:

`python3 -m venv venv`

Install Spacy and Jupyter into the venv:

`./venv/bin/pip install spacy jupyter`

Install the Spacy [language models](https://spacy.io/usage/models#section-available):

`./venv/bin/python -m spacy download en_core_web_sm`

`./venv/bin/python -m spacy download de_core_news_sm`

Run the Jupyter notebook:

`./venv/bin/jupyter-notebook entity_recognition.ipynb`
