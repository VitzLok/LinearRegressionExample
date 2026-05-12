# LinearRegressionExample

Projeto simples de Regressão Linear utilizando Python e NumPy para calcular previsões com base em dados numéricos.

---

## 📌 Descrição

O projeto implementa uma classe chamada `LinearRegression` responsável por:

* Calcular o coeficiente de correlação;
* Determinar a inclinação da reta;
* Calcular o intercepto;
* Realizar previsões com base em um valor informado pelo usuário.

O algoritmo utiliza conceitos estatísticos básicos aplicados à regressão linear simples.

---

## 🛠️ Tecnologias Utilizadas

* Python 3
* NumPy

---

## 📂 Estrutura do Projeto

```bash
LinearRegressionExample/
│
├── main.py
└── README.md
```

---

## 📖 Como Funciona

A regressão linear busca encontrar uma reta capaz de representar a relação entre dois conjuntos de dados (`X` e `Y`).

A fórmula utilizada é:

$$
y = a + bx
$$

Onde:

* `a` → intercepto;
* `b` → inclinação da reta;
* `x` → valor informado;
* `y` → previsão calculada.

---

## ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/LinearRegressionExample.git
```

Acesse a pasta:

```bash
cd LinearRegressionExample
```

Instale o NumPy:

```bash
pip install numpy
```

---

## ▶️ Executando o Projeto

Execute o arquivo Python:

```bash
python main.py
```

O programa solicitará um valor para realizar a previsão.

### Exemplo

Entrada:

```text
Digite um valor para que seja feita a previsão: 6
```

Saída:

```text
A previsão foi feita e o número que equivale a Y na matriz de X é: 3.0
```

---

## 🧠 Explicação do Código

### Classe `LinearRegression`

A classe recebe dois arrays:

```python
x = array([1,2,3,4,5])
y = array([2,4,6,8,10])
```

---

### Métodos principais

#### `__correlacao()`

Calcula o coeficiente de correlação entre `X` e `Y`.

---

#### `__inclinacao()`

Calcula a inclinação da reta.

---

#### `__interceptacao()`

Calcula o ponto onde a reta intercepta o eixo Y.

---

#### `previsao(valor)`

Retorna a previsão com base no valor informado.

---

## 📊 Exemplo Matemático

Com os dados:

```python
X = [1,2,3,4,5]
Y = [2,4,6,8,10]
```

A reta encontrada seria:

$$
y = 2x
$$

---

## 📚 Conceitos Utilizados

* Regressão Linear Simples
* Estatística
* Covariância
* Variância
* Correlação
* Predição de Dados

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de estudo e aprendizado em Machine Learning e Estatística com Python.

---

## 📄 Licença

Este projeto está sob a licença MIT.
