# Diabetes BI & Analytics
Este projeto tem como objetivo analisar fatores de risco associados ao diabetes utilizando técnicas de Business Intelligence (BI), Analytics e Machine Learning, integrando uma solução completa composta por:

- Pré-processamento de dados em Python  
- Análise exploratória  
- Modelo preditivo (Random Forest)  
- Painéis interativos no Power BI  
- Documentação executiva e técnica  

O projeto foi desenvolvido como entrega da Fase 2 da disciplina de Business Intelligence e Analytics, seguindo as orientações do template institucional.

---

##  1. Objetivos do Projeto
- Identificar os principais fatores de risco associados ao diabetes.  
- Criar indicadores e métricas estratégicas relacionados aos hábitos e condições clínicas da população estudada.  
- Desenvolver visualizações em Power BI para apoiar análise e tomada de decisão.  
- Construir um modelo de machine learning capaz de predizer a probabilidade de diabetes.  
- Documentar o processo de coleta, tratamento e análise dos dados.

---

## 2. Principais KPIs do Projeto
Os indicadores estratégicos utilizados na solução foram:

- **Prevalência de diabetes:** 13,93%  
- **IMC médio da população:** 28,38  
- **Percentual de obesidade:** 34,63%  
- **Pacientes em categoria “Alto Risco”:** 36%  
- **Total de registros analisados:** ~254.000

Esses KPIs foram utilizados na Página 1 — Visão Geral do dashboard.

---

## 3. Insights Identificados

### Fatores Demográficos
- A prevalência de diabetes cresce significativamente nas faixas etárias de 70–79 anos, com picos de 21,85% (70–74) e 21,30% (75–79).

### Gênero
- A distribuição é equilibrada:  
  - **Mulheres:** 52%  
  - **Homens:** 48%  
  → Gênero não é forte discriminador de risco.

### IMC e Obesidade
- A maior incidência de diabetes ocorre nas categorias de Obesidade I, II e III.  
- Indivíduos com peso normal apresentam as menores taxas da doença.

### Colesterol Alto
- 23.689 indivíduos têm colesterol alto E diabetes.  
- 11.660 têm colesterol alto mas não têm diabetes.  
→ Forte associação metabólica.

### Categoria de Risco
- 43% da amostra está em risco moderado.  
- 36% está em alto risco (principal grupo para intervenção).

---

## 4. Modelo Preditivo (Analytics)
O modelo escolhido foi o Random Forest Classifier, por apresentar:

- boa capacidade de generalização  
- manejo eficiente de variáveis categóricas  
- robustez contra desbalanceamento  
- interpretabilidade via feature importance  

Principais fatores que influenciaram o risco predito:

1. Faixa Etária  
2. IMC  
3. Categoria de Risco  
4. Pressão Alta  
5. Colesterol Alto  

---

## 5. Tecnologias Utilizadas

### Python
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

### BI e Visualização
- Power BI Desktop  
- Dashboards publicados via Power BI Service  

### Versionamento
- GitHub (código, notebooks e documentação)

---

## 6. Como Executar o Projeto

### Pré-requisitos
- Python 3.10+  
- pip instalado  
- Power BI Desktop  

### Passos

```bash
# Clonar o repositório
git clone https://github.com/SEU_USUARIO/diabetes-bi-analytics

# Entrar na pasta
cd diabetes-bi-analytics
```
## 7. Autora
Gabriella Gomes
Disciplina: Projeto Em Business Intelligence e Analytics
Instituição: PUCRS 


