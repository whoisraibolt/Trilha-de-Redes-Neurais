# Trilha de Redes Neurais (SLP → MLP → CNN) 🧠📚

Este repositório organiza uma trilha prática de redes neurais em Jupyter Notebook, indo do básico ao estado-da-arte em visão computacional.

## 🧭 Ordem recomendada de estudo

1. `01_Single_Layer_Perceptron.ipynb` — SLP (Perceptron)
2. `02_MLP_MNIST.ipynb` — MLP no MNIST
3. `03_Convolution_Feature_Maps_MNIST.ipynb` — Convolução e **feature maps** (efeito de filtros diferentes) 🧩🖼️
4. `04_CNN_MNIST_e_Transfer_Learning.ipynb` — CNN no MNIST + **Transfer Learning** 🚀

## 📁 Estrutura de arquivos

- `01_Single_Layer_Perceptron.ipynb` — implementação didática do Perceptron de camada única (adaptada de `whoisraibolt/Single-Layer-Perceptron`).
- `02_MLP_MNIST.ipynb` — exemplo de MLP (Dense + ReLU + Dropout + Softmax) com treinamento e avaliação.
- `03_Convolution_Feature_Maps_MNIST.ipynb` — demonstração visual de como kernels diferentes geram feature maps diferentes.
- `04_CNN_MNIST_e_Transfer_Learning.ipynb` — tutorial completo de CNN com MNIST, métricas, transfer learning e CIFAR-10.
- `imagens/` — imagens usadas no material didático.

## ✅ Requisitos

- Python **3.10+** (recomendado)
- Jupyter Notebook ou JupyterLab
- Bibliotecas:
  - `tensorflow`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `seaborn`
  - `networkx`
  - `plotly`

## ⚙️ Setup local com `venv`

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
# .venv\Scripts\activate   # Windows

pip install --upgrade pip
pip install tensorflow numpy matplotlib scikit-learn seaborn networkx plotly jupyter
```

## 🐍 Setup com Conda

```bash
conda create -n nn-trilha python=3.10 -y
conda activate nn-trilha
pip install tensorflow numpy matplotlib scikit-learn seaborn networkx plotly jupyter
```

## ▶️ Como executar os notebooks localmente

```bash
jupyter notebook
```

> Observação: datasets padrão (MNIST e CIFAR-10) são baixados automaticamente pelo TensorFlow na primeira execução.

## ☁️ Como rodar no Google Colab

1. Abra o Colab: https://colab.research.google.com/
2. Escolha **File > Open notebook > GitHub**.
3. Informe o repositório `whoisraibolt/aaa`.
4. Abra o notebook desejado.
5. Se necessário, execute uma célula de instalação:

```python
!pip install tensorflow numpy matplotlib scikit-learn seaborn networkx plotly
```

## ♻️ Reprodutibilidade

Os notebooks `01_Single_Layer_Perceptron.ipynb` e `02_MLP_MNIST.ipynb` definem seeds para tornar os resultados mais reproduzíveis.
