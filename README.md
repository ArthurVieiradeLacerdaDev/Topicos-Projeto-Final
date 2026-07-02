# Projeto de Automação na Análise de Dados da Crise Global da Água Potável

**Instituição:** UNIVERSIDADE FEDERAL DO CEARÁ - CAMPUS SOBRAL  
**Curso:** ENGENHARIA DE COMPUTAÇÃO  
**Disciplina:** TÓPICOS ESPECIAIS EM COMPUTAÇÃO I (2026.1) - CIÊNCIA DE DADOS 
**Professor:** PROF. IÁLIS CAVALCANTE DE PAULA JUNIOR  

---

## 👥 Equipe
* ARTHUR VIEIRA DE LACERDA FIALHO
* ALISSON DOS SANTOS NASCIMENTO
* EDUARDO SANTOS DE CASTRO
* JONATHAN FERNANDES DA COSTA
* VICTOR EMANUEL FONTENELE LIMA
* MARINA PAULA FONTENELE
* RYAN GOMES MAGALHAES LIMA

---

## 🎯 Objetivo do Projeto
O objetivo deste projeto é construir e avaliar modelos preditivos de classificação supervisionada para determinar se uma amostra de água é potável ou não. Esta iniciativa visa servir como uma ferramenta de triagem automatizada e barata para populações vulnerávei, considerando que bilhões de pessoas sofrem com a falta de acesso à água segura para consumo, segundo a Organização Mundial da Saúde (OMS) e a UNICEF.

A metodologia do projeto inclui análise de amostras de água por meio de processos automatizados, análise estatística e o treinamento e teste de pelo menos três algoritmos de aprendizagem supervisionada para classificação.

---

## 📊 Base de Dados (Dataset)
Utilizamos o dataset **Water Potability**, hospedado no Kaggle (https://www.kaggle.com/datasets/adityakadiwal/water-potability). O dataset possui desafios técnicos, incluindo desbalanceamento e dados ausentes que exigiram tratamento prévio.

### Descrição dos Atributos
* **ph:** Medida do equilíbrio ácido-base da água (escala de 0 a 14).
* **Hardness:** Dureza da água, causada principalmente por sais de cálcio e magnésio (em mg/L).
* **Solids:** Sólidos Dissolvidos Totais (TDS), indicando o nível de mineralização (em ppm).
* **Chloramines:** Concentração de cloraminas, principais desinfetantes usados em sistemas públicos (em ppm).
* **Sulfate:** Concentração de sulfatos, substâncias abundantes na atmosfera e solo (em mg/L).
* **Conductivity:** Condutividade elétrica da água, ligada à presença de sólidos dissolvidos (μS/cm).
* **Organic_carbon:** Carbono orgânico total (TOC), mede o nível de matéria orgânica na amostra (em ppm).
* **Trihalomethanes:** Concentração de trihalometanos, subprodutos químicos gerados no tratamento da água (μg/L).
* **Turbidity:** Turbidez da água, que mede as propriedades de emissão de luz dependendo de matéria suspensa (NTU).
* **Potability (Atributo-alvo):** 1 se a água é potável (segura para consumo humano), 0 se não é potável.

---

## 🛠️ Tecnologias e Algoritmos Utilizados
* **Linguagem:** Python
* **Bibliotecas:** Pandas, Scikit-learn, XGBoost, Imbalanced-learn (SMOTE)
* **Algoritmos de Classificação:** Regressão Logística, Random Forest e XGBoost.
* **Rastreamento e Comunicação de Resultados:** ML Flow (https://mlflow.org/).

---

## ⚙️ Instruções de Instalação e Configuração

Os passos a seguir incluem todas as instruções necessárias para instalação, configuração e execução do projeto.
