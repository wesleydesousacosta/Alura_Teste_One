# Alura_Teste_One
# ☕📊 Análise de Consumo de Café e Qualidade do Sono

## 📌 Visão Geral do Projeto

Este projeto foi desenvolvido para a empresa fictícia **Health&Life Analytics**, com o objetivo de **analisar o perfil de clientes e entender como o consumo de café, o estresse e fatores demográficos impactam a qualidade do sono**.

O trabalho envolve:
- Análise Exploratória de Dados (EDA)
- Visualizações com insights de negócio
- Criação de um **modelo preditivo** para classificar a **qualidade do sono (Sleep_Quality)**
- Geração de recomendações estratégicas baseadas nos resultados

---

## 🎯 Objetivos

- Explorar padrões e relações entre consumo de café, estresse e sono
- Comunicar insights de forma clara por meio de visualizações
- Treinar e comparar modelos de classificação
- Apoiar decisões de negócio com base em dados

---

## 🗂 Estrutura do Repositório


---

## 📊 Dataset

- **Nome:** `synthetic_coffee_health_10000.csv`
- **Descrição:** Dataset sintético contendo informações sobre:
  - Consumo de café
  - Qualidade e duração do sono
  - Níveis de estresse
  - Idade e gênero
- **Disponibilidade:**  
  O dataset está disponível na pasta `/data` ou pode ser carregado diretamente do Google Drive conforme indicado no notebook.

---

## 🧪 Bibliotecas Utilizadas

O projeto foi desenvolvido em **Python** e utiliza as seguintes bibliotecas:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `joblib`

---

## 🚀 Como Rodar o Projeto

### 🔹 Opção 1: Google Colab (Recomendado)

1. Abra o Google Colab
2. Faça upload do notebook ou clone o repositório
3. Monte o Google Drive (caso utilize o caminho do Drive)
4. Execute todas as células em ordem

O notebook foi desenvolvido para rodar **sem erros** no Google Colab.

---

### 🔹 Opção 2: Jupyter Notebook (Local)

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

Instale as dependências:
pip install pandas numpy matplotlib seaborn scikit-learn joblib

Abra o notebook:
jupyter notebook

modelos_machine_learning:
  modelos_treinados:
    - nome: Regressao Logistica
      tipo: classificacao
    - nome: Random Forest
      tipo: classificacao
      melhor_desempenho: true

  metricas_avaliacao:
    - acuracia
    - matriz_de_confusao
    - relatorio_de_classificacao

  modelo_final_salvo:
    arquivo: modelo_sleep_quality.pkl

principais_resultados:
  - descricao: Alto consumo de cafe
    impacto: Associado a menor qualidade do sono
  - descricao: Estresse
    impacto: Um dos fatores mais relevantes para a predicao
  - descricao: Modelo Random Forest
    impacto: Melhor performance geral entre os modelos testados
  - descricao: Aplicabilidade
    impacto: Resultados permitem alertas personalizados e recomendacoes de habitos saudaveis

recomendacoes_de_negocio:
  - acao: Reduzir consumo de cafeina
    publico_alvo: Clientes com alto nivel de estresse
  - acao: Implementar programas de bem-estar
    foco: Qualidade do sono
  - acao: Uso do modelo preditivo
    objetivo: Prever riscos e orientar mudancas de habitos

requisitos_atendidos:
  repositorio_publico: true
  readme_documentado: true
  execucao_sem_erros:
    jupyter_notebook: true
    google_colab: true
  dataset_disponivel_ou_indicado: true

