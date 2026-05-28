# 📦 Análise de Produtos com Pandas

Projeto de análise exploratória de dados de vendas de uma loja de roupas e acessórios, utilizando Python e Pandas.

---

## 📁 Arquivos

| Arquivo | Descrição |
|---|---|
| `produtos.csv` | Base de dados com 20 produtos |
| `produtoscsv.ipynb` | Notebook com toda a análise |

---

## 📊 O que foi analisado

- **Desempenho por categoria** — total de unidades vendidas por categoria (Roupas, Calçados, Acessórios)
- **Produto mais vendido** — identificação via `idxmax()`
- **Total de unidades por produto** — ranking completo de vendas
- **Correlação Quantidade x Preço** — relação entre preço e volume vendido

---

## 🔍 Principais resultados

| Métrica | Resultado |
|---|---|
| Categoria mais vendida | Roupas (163 unidades) |
| Produto mais vendido | Brinco / Camiseta (30 unidades) |
| Correlação Preço x Quantidade | -0.72 (negativa forte) |

> Produtos mais caros tendem a vender menos — comportamento esperado no varejo.

---

## 🛠️ Tecnologias

- Python 3.13
- Pandas
- Jupyter Notebook

---

## ▶️ Como executar

```bash
# Clone o repositório
git clone https://github.com/ardosnt/An-lise-de-Produtos-com-Pandas.git

# Instale as dependências
pip install pandas jupyter

# Abra o notebook
jupyter notebook produtoscsv.ipynb
```

---

## 👤 Autor

Feito como exercício prático de análise de dados com Pandas.
