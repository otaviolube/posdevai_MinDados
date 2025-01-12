# Mineração de Dados

**Prof. Dr. Sergio N. Simões**  
**Pós-graduação em Desenvolvimento de Aplicações Inteligentes**  
**Disciplina:** Mineração de Dados  
**Aluno:** Otávio Lube dos Santos  
**Matrícula:** 20231DEVAI0157  

---

## Descrição

Este repositório contém as atividades realizadas na disciplina de **Mineração de Dados**, ministrada pelo Prof. Dr. Sergio N. Simões, durante o curso de Pós-Graduação em Desenvolvimento de Aplicações Inteligentes. Os trabalhos envolvem análises práticas utilizando conceitos de mineração de dados, com ferramentas como Python, bibliotecas de machine learning e SHAP para explicabilidade de modelos.

---

## Estrutura do Repositório

O repositório está organizado da seguinte forma:

```
├── trabalho1/
│   ├── trabalho1.ipynb
│   ├── trabalho1.pdf
│   ├── trabalho1_report.md
│   └── segmentarion_data.csv (arquivos de dados utilizados no trabalho 1)
├── trabalho2/
│   ├── trabalho2.ipynb
│   ├── trabalho2.pdf
│   └── housing.csv (arquivos de dados utilizados no trabalho 2)
├── trabalho3/
│   ├── trabalho3.ipynb
│   ├── trabalho3.pdf
├── README.md
```

---

## Trabalhos Realizados

### Trabalho 1: Análise Exploratória e Clustering
- **Objetivo:** Realizar análise exploratória dos dados, aplicar métodos de clustering (agrupamento) e interpretar os resultados.
- **Atividades Realizadas:**
  - Análise exploratória das distribuições de atributos.
  - Geração de gráficos de clustering.
  - Discussão sobre estratégias de marketing baseadas em clusters identificados.
- **Ferramentas Utilizadas:**  
  Python, bibliotecas de visualização (Matplotlib, Seaborn) e Scikit-learn.

### Trabalho 2: Regressão Linear e Seleção de Variáveis
- **Objetivo:** Aplicar modelos de regressão linear múltipla e explorar métodos de seleção de variáveis.
- **Atividades Realizadas:**
  - Comparação de modelos de regressão utilizando métricas como R² e MSE.
  - Implementação de métodos de seleção de variáveis, incluindo Forward Selection.
  - Explicação teórica sobre correlação e impactos da multicolinearidade.
- **Ferramentas Utilizadas:**  
  Python, Scikit-learn e bibliotecas de visualização.

### Trabalho 3: Explicabilidade com SHAP
- **Objetivo:** Utilizar a biblioteca SHAP para explicar os modelos de machine learning.
- **Atividades Realizadas:**
  - Geração de gráficos SHAP (Summary Plot, Waterfall Plot, Dependence Plot).
  - Discussão sobre explicabilidade global e local.
  - Interpretação dos resultados de importância das características.
- **Ferramentas Utilizadas:**  
  Python, bibliotecas SHAP e XGBoost.

---

## Como Executar os Trabalhos

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/repositorio-mineracao-dados.git
   ```
2. Navegue até o diretório do trabalho desejado:
   ```bash
   cd trabalho1
   ```
3. Crie um ambiente virtual e instale as dependências:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
4. Abra o notebook no Jupyter:
   ```bash
   jupyter notebook trabalho1.ipynb
   ```

---

## Requisitos

- Python 3.11 ou superior.
- Bibliotecas necessárias:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`
  - `shap`
- Instale todas as dependências utilizando:
  ```bash
  pip install -r requirements.txt
  ```

---

## Licença

Este repositório é destinado apenas para fins acadêmicos. Todo o conteúdo aqui apresentado foi desenvolvido como parte das atividades da disciplina **Mineração de Dados**.
