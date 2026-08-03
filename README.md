# Demanda de Mercado para um Curso Online

Projeto de análise de dados desenvolvido para avaliar a viabilidade do lançamento de um curso online de **Técnicas de Trading Algorítmico** a partir de uma pesquisa de mercado com 120 respondentes.

O estudo combina **Análise Exploratória de Dados (EDA)** e **Inferência Estatística** para responder às principais perguntas de negócio da startup.

[![Medium](https://img.shields.io/badge/Artigo-Medium-black?logo=medium)](https://medium.com/@luizamarchenib/demanda-de-mercado-para-um-curso-online-an%C3%A1lise-preditiva-do-interesse-e-da-disposi%C3%A7%C3%A3o-a-pagar-dos-46350adc32ad?postPublishedType=repub)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luizamb2306/demanda-mercado-curso-online/blob/main/demanda_curso_online.ipynb)

---

## Objetivos

- Estimar a proporção de pessoas interessadas no curso.
- Estimar o preço médio que os interessados estariam dispostos a pagar.
- Identificar o perfil dos potenciais clientes interessados.
- Avaliar se o lançamento do curso atende aos critérios mínimos definidos pela startup.

---

## Técnicas utilizadas

- Estatística descritiva
- Análise univariada e bivariada
- Information Value (IV)
- Intervalos de confiança
- Testes de hipóteses

---

## Ferramentas

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib

---

## Estrutura do projeto

```text
.
├── demanda_curso_online.ipynb   # Código completo da análise
├── dados_pesquisa.xlsx          # Base de dados
├── requirements.txt             # Dependências do projeto
└── README.md
```

---

## Principais resultados

- A proporção estimada de interessados foi superior ao mínimo de **25%** estabelecido pela startup.
- O preço médio estimado ficou acima do valor mínimo de **R$85**, indicando potencial viabilidade econômica.
- A variável **faixa etária** apresentou maior capacidade de diferenciar interessados e não interessados, enquanto sexo e escolaridade não demonstraram associação relevante.

---

## Como reproduzir a análise

A maneira mais simples é abrir o notebook diretamente no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/luizamb2306/demanda-mercado-curso-online/blob/main/demanda_curso_online.ipynb)

Caso prefira executar localmente:

```bash
git clone https://github.com/luizamb2306/demanda-mercado-curso-online.git

cd demanda-mercado-curso-online

pip install -r requirements.txt

jupyter notebook demanda_curso_online.ipynb
```

---

## Artigo completo

A descrição detalhada da metodologia, dos resultados e das conclusões está disponível no Medium:

[**Demanda de Mercado para um Curso Online: Análise Preditiva do Interesse e da Disposição a Pagar**](https://medium.com/@luizamarchenib/demanda-de-mercado-para-um-curso-online-an%C3%A1lise-preditiva-do-interesse-e-da-disposi%C3%A7%C3%A3o-a-pagar-dos-46350adc32ad?postPublishedType=repub)
