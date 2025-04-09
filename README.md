 Previsão de Inadimplência de Clientes

## 📌 Descrição do Projeto
Este projeto tem como objetivo prever a **inadimplência de clientes** com base em características sociodemográficas e comportamentais. A iniciativa envolve desde a **análise exploratória dos dados** até a **construção e avaliação de modelos preditivos de Machine Learning**, com foco na **identificação de perfis de maior risco**.

O modelo final visa **apoiar decisões estratégicas** na concessão de crédito, promovendo uma **gestão mais eficiente da carteira de clientes** e **redução de perdas financeiras**.

---

## 🗂️ Estrutura do Repositório
```
📁 dados/
    └── arquivos CSV utilizados no projeto
📁 notebooks/
    └── Previsao_de_inadimplencia_de_clientes.ipynb
📄 README.md
```

---

## 🔍 Etapas do Projeto

### 1. Entendimento do Problema e Análise Exploratória
- Compreensão dos fatores associados à inadimplência.
- Análise da variável alvo `default` (inadimplente ou adimplente).
- Geração de visualizações para investigar o comportamento dos grupos.

### 2. Pré-processamento e Preparação dos Dados
- Tratamento de dados faltantes e outliers.
- Codificação de variáveis categóricas.
- Padronização de variáveis numéricas.

### 3. Seleção de Atributos Relevantes
- Análise de correlações.
- Avaliação de importância das variáveis por meio de SHAP values.

### 4. Modelagem Preditiva
- Treinamento de algoritmos como **Decision Tree** e **Random Forest**.
- Otimização e validação do modelo **XGBoost**, com desempenho final:
  - Acurácia: **93,88%**
  - Recall: **90,61%**
  - Precision: **74,67%**
  - F1-Score: **81,87%**
  - AUC-ROC: **98,59%**

### 5. Interpretação dos Resultados
- Identificação de variáveis mais impactantes:
  - `qtd_transacoes_12m`, `valor_transacoes_12m` e `meses_inativo_12m`.
- Insights estratégicos para mitigação de risco.

### 6. Relevância para o Negócio
- Apoio à tomada de decisão na concessão de crédito.
- Potencial de integração com sistemas de análise em tempo real.
- Propostas de melhorias e monitoramento contínuo.

---

## 🛠 Tecnologias Utilizadas
- **Linguagem**: Python  
- **Bibliotecas**:  
  - Manipulação: `Pandas`, `NumPy`, `Plotly`  
  - Visualização: `Matplotlib`, `Seaborn`  
  - Modelagem: `Scikit-Learn`, `XGBoost`, `SHAP`

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
```bash
git clone https://github.com/IsabelleFernanda/Previsao-de-Inadimplencia/.git
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute o notebook:
Abra o arquivo `Previsao_de_inadimplencia_de_clientes.ipynb` no Google Colab, Jupyter Notebook ou Jupyter Lab e execute as células na ordem.

---

## 💡 Contribuições
Contribuições são bem-vindas!  
Se você tiver sugestões, ideias ou melhorias, fique à vontade para abrir uma *issue* ou enviar um *pull request*.

---

## 👩‍💻 Autora

**Isabelle Fernanda**  
[Cientista de Dados em formação pela EBAC](https://www.linkedin.com/in/isabellefernandasilva/)  
Projeto desenvolvido como parte da formação em Ciência de Dados – EBAC (Escola Britânica de Artes Criativas e Tecnologia)
