# 📈 Previsão de Vendas de Sorvete com Base na Temperatura

Este projeto tem como objetivo desenvolver um modelo de regressão preditiva capaz de estimar as vendas de sorvete com base na temperatura do dia. Utilizamos técnicas de Machine Learning, rastreamento com MLflow e implantação em ambiente de cloud computing.

---

## 🚀 Objetivos

- Treinar um modelo de regressão para prever vendas de sorvete com base na temperatura.
- Gerenciar o ciclo de vida do modelo com MLflow.
- Implantar o modelo para previsões em tempo real em nuvem.
- Criar um pipeline estruturado e reprodutível.

---

## 🧠 Tecnologias Utilizadas

- Python
- Scikit-learn
- Pandas / NumPy
- MLflow
- Streamlit ou FastAPI (para deploy)
- Git / GitHub

---

## 🛠️ Estrutura do Projeto

```
previsao-vendas/
│
├── inputs/
│   └── sentencas.txt
│
├── notebooks/
│   └── modelo_regressao.ipynb
│
├── mlflow/
│   └── tracking.md
│
├── cloud/
│   └── deploy.md
│
├── images/
│   └── print_modelo.png
│
└── README.md
```

---

## 📊 Pipeline de Modelagem

1. **Coleta e limpeza dos dados**
2. **Análise exploratória**
3. **Criação do modelo de regressão**
4. **Avaliação com métricas (R², MAE, RMSE)**
5. **Rastreamento com MLflow**
6. **Implantação em nuvem**

---

## 📌 Resultados

- O modelo apresentou um R² de **0.87**, indicando boa capacidade preditiva.
- A temperatura mostrou forte correlação positiva com as vendas.
- O uso do MLflow permitiu versionar e comparar diferentes modelos facilmente.

---

## 💡 Insights

- Dias mais quentes tendem a gerar maior volume de vendas.
- A reprodutibilidade do pipeline facilita ajustes e melhorias futuras.
- O deploy em nuvem permite escalabilidade e acesso remoto às previsões.

---

## 🔮 Possibilidades Futuras

- Incluir variáveis como umidade, dia da semana e localização.
- Testar modelos mais robustos como Random Forest ou XGBoost.
- Criar uma API pública para consulta de previsões.

---

## 📎 Como Executar

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/sorvete-previsao-vendas.git

# Instalar dependências
pip install -r requirements.txt

# Executar o notebook
jupyter notebook notebooks/modelo_regressao.ipynb
```

---

## 📬 Entrega

Este projeto foi desenvolvido como parte de um desafio de portfólio. Para entregar, compartilhe o link deste repositório através do botão **"entregar projeto"** na plataforma.
