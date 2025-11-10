# 🏥 Projeto de Data Science – Previsão de Readmissão Hospitalar

Este repositório contém o projeto completo de Data Science desenvolvido para analisar dados hospitalares simulados e prever a readmissão de pacientes em até 30 dias.  
O projeto segue o fluxo completo de um trabalho real de Data Science:

- Carregamento e inspeção dos dados  
- Análise Exploratória (EDA)  
- Pré-processamento  
- Modelagem preditiva com Random Forest  
- Avaliação do modelo  
- Conclusão e insights

---

## 📂 Estrutura do Repositório

📁 projeto-data-science/
├── notebook_pratica.ipynb # Notebook completo do projeto
├── dataset_saude_simulado.csv # Base de dados
├── parte_pratica.pdf # PDF final gerado pelo notebook
└── README.md # Este arquivo


---

## 📊 Tecnologias Utilizadas

- **Python 3.11+**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-Learn**
- **Jupyter Notebook**

---

## 🔎 Etapas do Projeto

### 1️⃣ Análise Exploratória (EDA)
Foram gerados:

- Histograma de idade  
- Boxplot do tempo de espera  
- Mapa de correlação entre variáveis  
- Estatísticas descritivas  

Essas etapas ajudaram a entender o comportamento dos pacientes e identificar fatores relacionados à readmissão.

---

### 2️⃣ Modelagem Preditiva
O modelo utilizado foi **Random Forest**, por ser robusto e lidar bem com múltiplas features.

Variáveis utilizadas:

- Idade  
- Pressão sistólica  
- Pressão diastólica  
- Satisfação do paciente  
- Tempo de espera  
- Diagnóstico crônico (sim/não)

---

### 3️⃣ Avaliação do Modelo

Métricas calculadas:

- **Acurácia**
- **ROC AUC**
- **Matriz de confusão**
- **Curva ROC**
- **Importância das features**

Os resultados mostraram boa capacidade do modelo para classificar pacientes com maior risco de readmissão.

---

## 🧠 Principais Insights

- Pacientes com **diagnóstico crônico** possuem maior risco de readmissão.
- **Tempo de espera** e **satisfação do paciente** influenciam diretamente a qualidade do atendimento.
- O modelo apresentou boa capacidade de separação entre as classes, apesar do dataset desbalanceado.

---

## 📌 Conclusão

O modelo Random Forest foi eficaz em prever a readmissão hospitalar e demonstrou o potencial da Ciência de Dados como ferramenta de apoio à gestão de saúde.  
Mesmo com dados simulados, o fluxo seguido é equivalente ao usado em ambientes reais, respeitando práticas profissionais de Data Science.

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
```bash
git clone https://github.com/SEU-USUARIO-NO-GITHUB/seu-repositorio.git

Crie um ambiente virtual:

python -m venv venv


Ative o ambiente virtual (Windows):

venv\Scripts\activate


Instale as dependências:

pip install -r requirements.txt


Inicie o Jupyter Notebook:

jupyter notebook

Diogo Carvalho
Estudante de Engenharia de Computação
Projeto para disciplina de Data Science


Abra o arquivo:
      
notebook_pratica.ipynb
