
# Evaluating LLM based applications

## Workshop description
It is so easy and quick to build a shiny PoC using LLMs and it is so hard to turn it into a production-grade LLM application. To succeed you need a robust evaluation framework, which you are going to use during the development and post-deployment of your LLM based app.

This workshop focuses on understanding evaluation-driven development and architecture of a LLM based app, building an evaluation framework for a LLM based app, establishing a test suite with evals and laying the monitoring foundations for it. All of it by leveraging Python OSS libraries.

## Requirements
### General requrements
* basic Python knowledge
* basic understanding of ML testing
* basic understanding of ML monitoring

### Optional requirements
* [uv](https://docs.astral.sh/uv/) for dependency management
* [poetry](https://python-poetry.org/) for dependency management
* Google account if you want to use [Google Colab](https://colab.research.google.com/)

## Usage

Clone this repo and navigate to its root folder

### with uv
Run the following code:
```bash
# create and activate venv, install dependencies
uv sync
```
### with poetry
Run the following code:
```bash
# configure poetry to use a local venv (optional):
poetry config virtualenvs.in-project true

# activate venv
poetry env activate

# install dependencies
poetry install

# start notebook from within the virtual environment
jupyter notebook
```
### with Google collab
1. Visit [Google Colab](https://colab.research.google.com/)
2. In the top left corner select "File" &#8594; "Open Notebook"
3. Under "GitHub", enter the URL of the repo of this workshop
4. Select one of the notebooks within the repo.
5. At the top of the notebook, run the following code:
```bash
!cd ./eval-llm-based-apps-jan2025
!pip install -r requirements.txt
```

## Video record
Re-watch [this YouTube stream](https://www.youtube.com/live/phpQ5hmC08E?feature=shared)

## Credits
This workshop was set up by @pyladiesams and @una-ai-mlops-agency

## Appendix
### Pre-Commit Hooks
To ensure our code looks beautiful, PyLadies Amsterdam uses pre-commit hooks. You can enable them by running `pre-commit install`. 
