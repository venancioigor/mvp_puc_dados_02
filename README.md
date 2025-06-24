# 🧠 Análise de Dados de AVC - Predição de AVC


## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Dataset](#-dataset)
- [Funcionalidades](#-funcionalidades)
- [Instalação](#-instalação)
- [Como Usar](#-como-usar)
- [Análises Realizadas](#-análises-realizadas)
- [Resultados](#-resultados)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias](#-tecnologias)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

---

## 🎯 Sobre o Projeto

Este projeto realiza uma **análise exploratória completa** de um dataset médico focado na predição de AVC (Acidente Vascular Cerebral). O objetivo é identificar padrões, correlações e fatores de risco que podem estar associados à ocorrência de AVC em pacientes.

### 🔬 Objetivos Principais

- **Identificar fatores de risco** para AVC
- **Analisar correlações** entre variáveis clínicas
- **Visualizar padrões** nos dados médicos
- **Preparar dados** para modelagem preditiva
- **Gerar insights** acionáveis para profissionais de saúde

---

## 📊 Dataset

O dataset contém informações de **pacientes** com diversas características demográficas, clínicas e comportamentais:

| Variável | Tipo | Descrição |
|----------|------|-----------|
| `id` | int | Identificador único do paciente |
| `gender` | categorical | Gênero (Male/Female/Other) |
| `age` | int | Idade do paciente |
| `hypertension` | binary | Hipertensão (0=Não, 1=Sim) |
| `heart_disease` | binary | Doença cardíaca (0=Não, 1=Sim) |
| `ever_married` | categorical | Status civil (Yes/No) |
| `work_type` | categorical | Tipo de trabalho |
| `Residence_type` | categorical | Tipo de residência (Urban/Rural) |
| `avg_glucose_level` | float | Nível médio de glicose |
| `bmi` | float | Índice de massa corporal |
| `smoking_status` | categorical | Status de tabagismo |
| `AVC` | binary | **Target** - Ocorrência de AVC (0=Não, 1=Sim) |

### 📈 Características do Dataset
- **Instâncias**: ~5,000 registros
- **Features**: 11 variáveis preditoras
- **Target**: Classificação binária (AVC/não AVC)
- **Desbalanceamento**: Dataset com poucos casos positivos

---

## ⚡ Funcionalidades

### 🔍 Análise Exploratória
- ✅ Estatísticas descritivas completas
- ✅ Análise de distribuições
- ✅ Detecção de outliers
- ✅ Análise de correlações
- ✅ Visualizações interativas

### 🛠️ Pré-processamento
- ✅ Tratamento de valores nulos
- ✅ Codificação de variáveis categóricas
- ✅ Normalização e padronização
- ✅ Divisão estratificada dos dados

### 📊 Visualizações
- ✅ Histogramas e boxplots
- ✅ Matriz de correlação (heatmap)
- ✅ Gráficos de barras comparativos
- ✅ Análise de distribuição por classes

---

## 🚀 Instalação

### Pré-requisitos
- Python 3.8+
- pip ou conda

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/AVC-analysis.git
cd AVC-analysis
```

### 2. Instale as dependências
```bash
pip install -r requirements.txt
```

### 3. Arquivo requirements.txt
```txt
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.11.0
scikit-learn>=1.0.0
jupyter>=1.0.0
```

## 📞 Contato

Para dúvidas, sugestões ou colaborações:

- **Email**: igorvmfreitas@gmail.com
- **LinkedIn**: [Seu Nome](https://linkedin.com/in/igor-venancio)


