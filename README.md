# Projeto de Predição de Rotatividade de Funcionários

Este projeto tem como objetivo prever o attrition (rotatividade) de funcionários utilizando técnicas de Machine Learning. A abordagem envolve desde a geração do dataset até a avaliação dos modelos preditivos, passando por etapas de tratamento de dados e modelagem.

## 📁 Estrutura dos Notebooks

1. **01-gera_dataset.ipynb**  
   - Simulação/geração de um dataset com características de funcionários.
   - Variáveis incluem idade, salário, satisfação no trabalho, entre outras.

2. **02-trata_dados.ipynb**  
   - Análise exploratória dos dados.
   - Tratamento de valores ausentes e outliers.
   - Codificação de variáveis categóricas.
   - Normalização de variáveis numéricas.

3. **03-data_modeling.ipynb**  
   - Divisão dos dados em treino e teste.
   - Balanceamento do dataset utilizando SMOTE.
   - Treinamento com diferentes algoritmos (como regressão logística).
   - Análise de importância das variáveis.

4. **04-predicao_avaliacao.ipynb**  
   - Predição nos dados de teste.
   - Avaliação dos modelos com métricas como:
     - Accuracy
     - Precision
     - Recall
     - F1-score
     - AUC-ROC
   - Visualização das curvas de desempenho.

## 🧠 Modelos Utilizados

- Regressão Logística
- Decision Tree
- Random Forest
- SVM
- XGBoost

## 🛠️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. Crie um ambiente virtual e ative-o:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate   # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute os notebooks na ordem:
   - `01-gera_dataset.ipynb`
   - `02-trata_dados.ipynb`
   - `03-data_modeling.ipynb`
   - `04-predicao_avaliacao.ipynb`

## 🧾 Requisitos

- Python 3.8+
- Bibliotecas principais:
  - pandas
  - numpy
  - scikit-learn
  - imbalanced-learn
  - matplotlib
  - seaborn
  - jupyter

## 📊 Resultados Esperados

Com base nas análises e modelagens, espera-se obter um modelo capaz de:
- Identificar os principais fatores associados à rotatividade.
- Prever com boa acurácia e recall quais funcionários têm maior risco de sair da empresa.
- Ajudar o RH a tomar decisões proativas e direcionadas.

## 📌 Contribuições Futuras

- Inclusão de modelos mais complexos.
- Implementação de pipeline automatizado.
- Deployment do modelo como API.