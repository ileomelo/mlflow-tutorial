# MLFlow

Destinado a aprender o funcionamento e principais conceitos do MLFlow para desenvolvimento de modelos de Machine Learning e Inteligencia Artificial.

Aprender sobre o uso dessa ferramenta viabilisara a produçao e gestao de diferentes modelos treinados.Bem como auxiliara na maneira de como os modelos sao selecionados para produçao.

Nesse projeto usei o [UV](https://docs.astral.sh/uv/), que é um Python package e um project manager, escrito em Rust

## Créditos

Gostaria de agradecer a [Teo Calvo](https://github.com/TeoCalvo) pelo excelente conteúdo e passo a passo que segui para desenvolver este projeto.
[Link do Projeto](https://github.com/TeoMeWhy/curso-mflow/tree/main)

### MLFlow Server

Aqui é onde o comando mlflow server será executado para iniciar o MLflow, e também onde os artefatos serão gerados.

```bash
cd MLFlow Server
uv venv                 # Cria o ambiente virtual
.venv\Scripts\activate  # Ativa o ambiente virtual no Windows
uv sync   
mlflow server           # Para inicializar o MLFlow
```

### Model Churn

Diretório de Machine Learning, onde construímos o modelo, armazenamos os dados e realizamos o treinamento.

```bash
cd Model Churn
uv venv                 # Cria o ambiente virtual
.venv\Scripts\activate  # Ativa o ambiente virtual no Windows
uv sync                 # Atualiza o environment
```

Caso esteja usando PIP

```bash
cd Model Churn
cd MLFlow Server
pip install -r requirements.txt
```
