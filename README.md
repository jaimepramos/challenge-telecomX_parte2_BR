# 📊 Telecom X - Parte 2: Previsão de Churn

Este repositório contém a segunda etapa do projeto Telecom X, focada no desenvolvimento de modelos de Machine Learning para prever a evasão de clientes (Churn).  
Objetivo principal: antecipar clientes com maior probabilidade de cancelar serviços para ações de retenção proativas.

**Status do Projeto:** Concluído ✅

---

## 🧠 Objetivos do Desafio

- Preparar e limpar os dados tratados na Parte 1.
- Realizar Feature Engineering (Encoding e Normalização).
- Treinar e comparar modelos de classificação (Regressão Logística e Random Forest).
- Analisar importância das variáveis para gerar insights de negócio.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Pandas & Numpy (manipulação de dados)
- Scikit-Learn (modelos ML / avaliação)
- Seaborn & Matplotlib (visualização e correlação)

---

## 📈 Pipeline do Projeto

1. **Pré-processamento**
   - Limpeza: remoção de `customerID`; tratamento de valores ausentes em `Charges.Total` (conversão numérica).
   - Encoding: `get_dummies` (One-Hot Encoding) para variáveis categóricas.
   - Escalonamento: `StandardScaler` para normalizar variáveis numéricas.

2. **Modelagem**
   - Regressão Logística (interpretabilidade).
   - Random Forest (robustez e não-linearidade).

3. **Métricas de Avaliação**
   - Foco principal em **Recall** na classe `Churn = Yes`.

---

## 💡 Principais Insights (Conclusão Estratégica)

- **Tipo de Contrato:** Month-to-month tem maior churn.
- **Serviço de Internet:** Fibra Ótica apresenta churn elevado.
- **Forma de Pagamento:** Cheque Eletrônico associado a maior churn.
- **Tenure:** primeiros 6 meses são pontos de maior risco.

### Estratégias Recomendadas

- Campanhas de fidelização: migração para planos anuais com descontos.
- Investigar infraestrutura de Fibra Ótica.
- Onboarding com acompanhamento próximo para novos clientes.

---

## 📁 Estrutura de Arquivos

- `telecomx_modelagem.ipynb`: Notebook com código completo.
- `telecomx_cleaned_tratado.csv`: Base de dados usada.
- `README.md`: documentação do projeto.

---

**Desenvolvido por:** Jaime Pereira  
**Cargo:** Analista de Machine Learning Júnior