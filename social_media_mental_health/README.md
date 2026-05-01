# 📱 Redes Sociais e Saúde Mental

Análise exploratória de dados investigando a relação entre o uso de telas e indicadores de saúde mental em uma amostra de 8.000 usuários.

---

## 📋 Sobre o Projeto

Este projeto foi desenvolvido com fins de estudo e construção de portfólio em Análise e Ciência de Dados. O objetivo foi verificar se o tempo e a forma de utilização de telas podem impactar a saúde mental dos usuários, medida por escalas clínicas (GAD-7 para ansiedade e PHQ-9 para depressão).

---

## 🗂️ Dataset

- **Fonte:** [Kaggle — Social Media and Mental Health](https://www.kaggle.com/datasets/bertnardomariouskono/social-media-and-mental-health)
- **Registros:** 8.000 usuários
- **Colunas:** 15 variáveis (demográficas, comportamentais e de saúde mental)
- **Natureza:** Conjunto de dados sintético, porém cientificamente fundamentado
- **Valores nulos:** Nenhum

### Principais variáveis

| Variável | Descrição |
|---|---|
| `Daily_Screen_Time_Hours` | Horas diárias de uso de tela |
| `Sleep_Duration_Hours` | Horas de sono por noite |
| `Late_Night_Usage` | Uso de telas após a meia-noite (0/1) |
| `Social_Comparison_Trigger` | Gatilho de comparação social (0/1) |
| `User_Archetype` | Perfil do usuário (4 categorias) |
| `Primary_Platform` | Plataforma principal utilizada |
| `GAD_7_Score` | Score de ansiedade (0–21) |
| `PHQ_9_Score` | Score de depressão (0–23) |

---

## 🛠️ Tecnologias Utilizadas

- Python 3.12
- Pandas
- NumPy
- Plotly Express
- Plotly Figure Factory
- Jupyter Notebook

---

## 📊 Análises Realizadas

- Distribuição dos scores de ansiedade (GAD-7) e depressão (PHQ-9)
- Matriz de correlação entre variáveis numéricas
- Tempo de tela vs. ansiedade por tipo de atividade (Active/Passive)
- Ansiedade por plataforma (boxplot + IQR)
- Análise por arquétipo de usuário (tempo de tela, ansiedade e sono)
- Impacto do uso após a meia-noite na saúde mental e no sono
- Análise do gatilho de comparação social
- Análise por gênero e faixa etária

---

## 🔍 Principais Achados

Identifiquei que a forma e a intensidade do uso de telas estão associadas a piores indicadores de saúde mental.

- **Arquétipos:** Usuários classificados como Hyper-Connected e Passive Scroller apresentaram mediana de ansiedade (GAD-7) de 10, contra 4 dos Digital Minimalists — uma diferença de 150%.

- **Sono:** Digital Minimalists dormem em média 6,9h contra 4,7h dos Hyper-Connected. Usuários que acessam telas após a meia-noite dormem cerca de 22,8% menos e apresentam níveis significativamente maiores de ansiedade e depressão.

- **Plataformas:** Instagram e TikTok, plataformas com foco em conteúdo passivo de curta duração, apresentaram mediana de ansiedade 14% acima das demais plataformas analisadas.

- **Comparação social:** Usuários com gatilho de comparação social ativo — que consideram que o conteúdo consumido causa inveja ou insegurança — têm média de ansiedade 43% maior.

- **Gênero e idade:** Não apresentaram diferença significativa nos níveis de ansiedade e depressão, sugerindo que os padrões identificados são transversais a esses grupos dentro da amostra estudada.

> ⚠️ **Importante:** As associações encontradas são correlacionais — correlação não implica causalidade. Ansiedade e depressão são condições multifatoriais, e outros elementos não presentes neste dataset podem contribuir para os desfechos observados.

---

## 📁 Estrutura do Projeto

```
📦 social-media-mental-health
 ┣ 📓 analysis.ipynb
 ┣ 📄 social_media_mental_health.csv
 ┗ 📄 README.md
```

---

## 👤 Autor

**Gabriel Magalhães**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriel-magalh%C3%A3es-160529323/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gahbrielms)
