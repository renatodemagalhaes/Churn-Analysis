
# 📊 Telecom X — Análise de Churn de Clientes

Projeto de **Data Analysis / Data Science** focado na análise de **evasão de clientes (churn)**, desenvolvido com o objetivo de demonstrar habilidades técnicas, analíticas e de comunicação de insights para tomada de decisão.

---

## 🧠 Visão Geral

A evasão de clientes é um dos principais desafios em empresas de telecomunicações.  
Neste projeto, utilizo **Python e bibliotecas de análise de dados** para explorar dados reais (formato JSON, via API), identificar padrões associados ao churn e preparar o terreno para modelos preditivos.

O foco está em:
- Entendimento do negócio
- Qualidade e preparação dos dados
- Geração de insights acionáveis
- Clareza na comunicação técnica

---

## 🎯 Objetivos

- Aplicar **ETL (Extração, Transformação e Carga)** em dados semiestruturados
- Conduzir uma **Análise Exploratória de Dados (EDA)** completa e bem documentada
- Identificar **fatores-chave relacionados ao churn**
- Criar **features relevantes** para Machine Learning
- Demonstrar boas práticas de organização e documentação

---

## 🗂️ Estrutura do Repositório

```
├── TelecomX_Data.json              # Dados extraídos da API
├── EDA_TelecomX_Churn.ipynb        # EDA com análise de correlação
└── README.md                       # Documentação do projeto
```

---

## 📘 Dados Utilizados

Os dados representam informações de clientes, incluindo:

- Perfil demográfico
- Tempo de relacionamento com a empresa
- Serviços contratados
- Informações financeiras
- Status de churn (variável alvo)

Formato original:
- **JSON**, simulando consumo de dados via API

---

## 🔍 Principais Análises e Insights

### ✔️ Churn e Contrato
- Clientes com contrato **Month-to-month** apresentam maior taxa de evasão
- Contratos de longo prazo reduzem drasticamente o churn

### ✔️ Tempo de Contrato (Tenure)
- Clientes novos são significativamente mais propensos a cancelar
- Os primeiros meses são críticos para retenção

### ✔️ Serviços Contratados
- Criação da feature **Total_Services**
- Clientes com maior número de serviços tendem a cancelar menos

### ✔️ Análise de Correlação
- Correlação negativa entre churn e:
  - Tempo de contrato
  - Quantidade de serviços
- Correlação positiva entre churn e cobrança mensal

---

## 🧩 Feature Engineering

Feature desenvolvida durante o EDA:

- **Total_Services**  
  Soma de todos os serviços contratados pelo cliente, utilizada como proxy de engajamento.

Essa feature mostrou forte potencial para modelos preditivos.

---

## 🛠️ Tecnologias e Ferramentas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git / GitHub

---

## 🚀 Próximos Passos Técnicos

- Preparação do dataset final para Machine Learning
- Treinamento de modelos:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting / XGBoost
- Avaliação com métricas orientadas a churn (Recall, ROC-AUC)
- Tradução dos resultados em **estratégias de retenção**

---

## 👤 Autor

Renato Magalhães - renatodemagalhaes@yahoo.com.br

Project Link: [https://github.com/renatodemagalhaes/Churn-Analysis]

Projeto desenvolvido como parte de um **portfólio profissional em Data Science**, com foco em análise de dados, pensamento analítico e resolução de problemas de negócio.

📫 Aberto a feedbacks, colaborações e oportunidades.

---

⭐ Se este projeto agregou valor ou despertou interesse, fique à vontade para explorar os notebooks!
