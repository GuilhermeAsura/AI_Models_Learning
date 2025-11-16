# 🧠 AI Models Learning - Study Repository 🚀

This repository serves as my personal collection of notes and practices in **Data Science**, **Machine Learning**, and **Deep Learning**. The goal is to document my learning process and build a portfolio of projects and experiments.

The main focus is the practical application of algorithms and understanding modern frameworks, with a special emphasis on **PyTorch** for Deep Learning applications.

## 📁 Repository Structure

The repository is organized into main topics, each containing notebooks (`.ipynb`) with implementations and explanations.

```
/
├── 📊 dados/                 # Datasets used in the notebooks
├── 🤖 ML/                    # Classic Machine Learning notebooks
├── 🔥 PyTorch_study/         # Focused studies on Deep Learning with PyTorch
└── 🧠 RNA/                   # Artificial Neural Network implementations
```

-----

### 🤖 ML (Machine Learning)

This section contains implementations of classic Machine Learning algorithms, primarily focused on classification using the *Soybeans* dataset.

  * **DecisionTree\_Soybeans.ipynb**: Implementation of Decision Trees.
  * **NaiveBayes\_Soybeans.ipynb**: Application of the Naive Bayes classifier.
  * **SVC\_Soybeans.ipynb**: Using Support Vector Machines (SVM/SVC) for classification.

### 🔥 PyTorch\_study (Deep Learning with PyTorch)

This is a structured series of notebooks following a course or focused study on PyTorch, covering everything from the basics to more advanced topics like Computer Vision.

  * **00\_PyTorch\_fundamenatls.ipynb**: Basic concepts and Tensors in PyTorch.
  * **01\_PyTorch\_.Workflow.ipynb**: The standard workflow of a PyTorch project (Data -\> Model -\> Training -\> Evaluation).
  * **02\_PyTorch\_nn\_classification.ipynb**: Building neural networks for classification problems.
  * **03\_PyTorch\_Computer\_Vision.ipynb**: Focus on Computer Vision (CNNs, image datasets).
  * **04\_PyTorch\_Custom\_Dataset.ipynb**: How to load and use custom datasets.
  * **helper\_functions.py**: Utility functions used across the notebooks.

### 🧠 RNA (Artificial Neural Networks)

This folder contains other studies and implementations of neural networks.

  * **Sequential-RNA\_Soybean.ipynb**: Implementation of a sequential model (likely Keras/TensorFlow or PyTorch) for the *Soybeans* dataset.
  * **linear\_regress.ipynb**: A notebook focused on the basic concept of Linear Regression.

-----

## 🛠️ Getting Started

To run these notebooks, you will need Python and Jupyter installed, along with the main Data Science libraries.

1.  **Clone this repository:**

    ```bash
    git clone [YOUR_REPOSITORY_URL]
    cd AI_Models_Learning
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install the dependencies:**
    (You could create a `requirements.txt` file, but for now, the main ones are)

    ```bash
    pip install jupyter pandas scikit-learn matplotlib torch torchvision
    ```

4.  **Start Jupyter:**

    ```bash
    jupyter notebook
    ```

-----


# 🧠 AI Models Learning - Repositório de Estudos e Práticas 🚀

Este repositório serve como minha coleção pessoal de anotações e práticas em **Data Science**, **Machine Learning** e **Deep Learning**. O objetivo é documentar meu aprendizado e criar um portfólio de projetos e experimentos.

O foco principal é a aplicação prática de algoritmos e a compreensão de frameworks modernos, com ênfase especial em **PyTorch** para aplicações de Deep Learning.

## 📁 Estrutura do Repositório

O repositório está organizado em tópicos principais, cada um contendo notebooks (`.ipynb`) com implementações e explicações.

```
/
├── 📊 dados/                 # Datasets usados nos notebooks
├── 🤖 ML/                    # Notebooks de Machine Learning Clássico
├── 🔥 PyTorch_study/         # Estudos focados em Deep Learning com PyTorch
└── 🧠 RNA/                   # Implementações de Redes Neurais Artificiais
```

-----

### 🤖 ML (Machine Learning)

Esta seção contém implementações de algoritmos clássicos de Machine Learning, focados principalmente em classificação usando o dataset *Soybeans*.

  * **DecisionTree\_Soybeans.ipynb**: Implementação de Árvores de Decisão.
  * **NaiveBayes\_Soybeans.ipynb**: Aplicação do classificador Naive Bayes.
  * **SVC\_Soybeans.ipynb**: Uso de Support Vector Machines (SVM/SVC) para classificação.

### 🔥 PyTorch\_study (Deep Learning com PyTorch)

Esta é uma série estruturada de notebooks acompanhando um curso ou estudo focado em PyTorch, cobrindo desde o básico até tópicos mais avançados como Visão Computacional.

  * **00\_PyTorch\_fundamenatls.ipynb**: Conceitos básicos e tensores no PyTorch.
  * **01\_PyTorch\_.Workflow.ipynb**: O fluxo de trabalho padrão de um projeto em PyTorch (Dados -\> Modelo -\> Treinamento -\> Avaliação).
  * **02\_PyTorch\_nn\_classification.ipynb**: Construção de redes neurais para problemas de classificação.
  * **03\_PyTorch\_Computer\_Vision.ipynb**: Foco em Visão Computacional (CNNs, datasets de imagem).
  * **04\_PyTorch\_Custom\_Dataset.ipynb**: Como carregar e usar datasets customizados.
  * **helper\_functions.py**: Funções utilitárias usadas nos notebooks.

### 🧠 RNA (Redes Neurais Artificiais)

Esta pasta contém outros estudos e implementações de redes neurais.

  * **Sequential-RNA\_Soybean.ipynb**: Implementação de um modelo sequencial (provavelmente Keras/TensorFlow ou PyTorch) para o dataset *Soybeans*.
  * **linear\_regress.ipynb**: Um notebook focado no conceito básico de Regressão Linear.

-----

## 🛠️ Como Começar

Para rodar esses notebooks, você precisará ter o Python e o Jupyter instalados, além das principais bibliotecas de Data Science.

1.  **Clone este repositório:**

    ```bash
    git clone [URL_DO_SEU_REPOSITÓRIO]
    cd AI_Models_Learning
    ```

2.  **Crie um ambiente virtual (recomendado):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    (Você pode criar um arquivo `requirements.txt`, mas por enquanto, as principais são)

    ```bash
    pip install jupyter pandas scikit-learn matplotlib torch torchvision
    ```

4.  **Inicie o Jupyter:**

    ```bash
    jupyter notebook
    ```