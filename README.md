# 🚢 Titanic Survival Analysis

> Um estudo clássico de Ciência de Dados sobre os fatores que influenciaram as taxas de sobrevivência no naufrágio do Titanic.

## 🎯 Objetivo do Projeto
O objetivo desta análise é identificar padrões nos dados dos passageiros para entender quem tinha mais chances de sobreviver ao desastre, utilizando técnicas de análise exploratória e estatística.

* Investigar o impacto da classe social (Socio-economic status) na sobrevivência.
* Analisar a influência de gênero e idade nas chances de resgate.
* Identificar correlações entre o local de embarque e a estrutura familiar dos passageiros.

---

## 🏗️ Estrutura do Projeto

```text
titanic-survival-analysis/
├── data/
│   └── train.csv                # Dataset original com os dados dos passageiros
├── notebooks/
│   └── titanic_survival_eda.ipynb # Notebook com a análise completa
└── README.md                    # Documentação e conclusões

🛠️ Tecnologias Utilizadas
Python 3.10

Pandas (Limpeza de dados e tratamento de valores nulos)

Seaborn & Matplotlib (Visualização de distribuições e correlações)

Numpy (Processamento numérico)

✅ Conclusões e Insights Estratégicos
A análise revelou padrões claros que refletem as normas sociais da época:

Mulheres e Crianças Primeiro: A taxa de sobrevivência entre mulheres foi drasticamente superior à dos homens (aproximadamente 74% vs 18%).

Desigualdade de Classe: Passageiros da 1ª Classe tiveram quase 3x mais chances de sobreviver do que passageiros da 3ª Classe, evidenciando a prioridade no acesso aos botes.

Impacto Familiar: Passageiros que viajavam sozinhos ou em famílias muito grandes tiveram menores taxas de sobrevivência do que famílias pequenas (2 a 4 pessoas).

💡 Habilidades Demonstradas
Data Cleaning: Tratamento de dados ausentes (como a coluna 'Age' e 'Cabin').

Feature Engineering: Criação de novas variáveis a partir de dados brutos.

Análise Comparativa: Uso de gráficos de calor (Heatmaps) e histogramas para validar hipóteses.

📄 Licença
Este projeto utiliza a licença MIT.
