# Demanda de Mercado para um Curso Online

Projeto de análise de dados desenvolvido para avaliar a viabilidade do lançamento de um curso online de **Técnicas de Trading Algorítmico** a partir de uma pesquisa de mercado com 120 respondentes.

O estudo combina **análise exploratória de dados (EDA)** e **inferência estatística** para responder às principais perguntas de negócio da startup.

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

```
.
├── demanda_curso_online.ipynb   # Código completo da análise
├── dados_pesquisa.xlsx          # Base de dados
└── requirements.txt      # Dependências do projeto
```

---

## Principais resultados

- A proporção estimada de interessados foi superior ao mínimo de **25%** estabelecido pela startup.
- O preço médio estimado ficou acima do valor mínimo de **R$85**, indicando potencial viabilidade econômica.
- A variável **faixa etária** apresentou maior capacidade de diferenciar interessados e não interessados, enquanto sexo e escolaridade não demonstraram associação relevante.

---

## Artigo completo

A explicação detalhada da metodologia, dos resultados e das conclusões está disponível no Medium:

https://medium.com/@luizamarchenib/demanda-de-mercado-para-um-curso-online-an%C3%A1lise-preditiva-do-interesse-e-da-disposi%C3%A7%C3%A3o-a-pagar-dos-46350adc32ad?postPublishedType=repub

---

## Como reproduzir a análise

1. Clone este repositório.
2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute o notebook `demanda_curso_online.ipynb`.

---
