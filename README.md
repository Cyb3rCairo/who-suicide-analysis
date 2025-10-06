# WHO Suicide Data Analysis

## Project Overview
A comprehensive data analysis of World Health Organization suicide statistics from 1979 to 2016, covering 141 countries. This project explores patterns, trends, and risk factors using Python, data visualization, and machine learning techniques.

## Key Objectives
- Analyze global suicide trends over 37 years
- Identify demographic patterns (age, gender, geographic)
- Develop clustering models to group countries by suicide characteristics
- Provide data-driven insights for public health policies

## Key Findings

### Major Insights
- **Gender Disparity**: Men account for approximately 75% of all recorded cases
- **Age Patterns**: Highest rates observed in 35-54 and 55-74 age groups
- **Geographic Trends**: Eastern European and former Soviet countries show consistently higher rates
- **Temporal Analysis**: Numbers remain persistently high despite annual fluctuations

### Geographic Analysis
- Interactive world maps showing total cases and rates per 100,000 inhabitants
- Country clustering reveals three distinct groups based on population and suicide patterns
- Regional patterns suggest strong socio-economic and cultural influences

## Technologies Used

### Data Analysis
- Python, Pandas, NumPy

### Visualization
- Matplotlib, Seaborn, Plotly

### Machine Learning
- Scikit-learn (K-Means, StandardScaler)

### Geospatial
- Geopandas, Folium

### Notebook
- Google Colab, Jupyter

## Project Structure

```
who-suicide-analysis/
├── who_new.py # Main analysis notebook
├── requirements.txt # Python dependencies
├── README.md # Project documentation
├── .gitignore # Git ignore rules
└── LICENSE # MIT License
```

## Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/Cyb3r-Cairo/who-suicide-analysis.git
cd who-suicide-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the analysis
```bash
jupyter notebook who_new.py
```

## Dataset Information

**Source:** World Health Organization (WHO)

**Time Period:** 1979-2016 (37 years)

**Countries:** 141 nations

**Key Variables:** Country, year, sex, age, suicide numbers, population

## Analytical Methods

### Data Preprocessing
- Country name standardization
- Missing value analysis (7% missing data)
- Data type conversion and validation

### Statistical Analysis
- Descriptive statistics and trend analysis
- Group comparisons (gender, age, geographic)
- Rate calculations per 100,000 inhabitants

### Machine Learning
- K-Means Clustering: Grouping countries into 3 clusters based on population and suicide patterns
- Feature Scaling: StandardScaler for normalized comparisons

### Visualization Techniques
- Interactive choropleth maps (Plotly)
- Time series analysis with trend lines
- Demographic breakdowns (bar charts, line plots)
- Cluster analysis scatter plots

## Results and Applications

### Public Health Implications

- Targeted prevention programs for high-risk demographics
- Evidence-based policy recommendations
- Resource allocation optimization

### Research Value
- Baseline for comparative studies
- Methodology for similar public health analyses
- Open data for academic research

## How to Contribute
We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- World Health Organization for making the data available
- Python data science community for excellent libraries
- Google Colab for computational resources

-------------------------------------------------------------------

# Análise de Dados de Suicídio da OMS

## Visão Geral do Projeto
Uma análise de dados abrangente das estatísticas de suicídio da Organização Mundial da Saúde de 1979 a 2016, cobrindo 141 países. Este projeto explora padrões, tendências e fatores de risco usando Python, visualização de dados e técnicas de aprendizado de máquina.

## Objetivos Principais
- Analisar as tendências globais de suicídio ao longo de 37 anos
- Identificar padrões demográficos (idade, gênero, geográficos)
- Desenvolver modelos de clusterização para agrupar países por características de suicídio
- Fornecer insights baseados em dados para políticas de saúde pública

## Principais Descobertas

### Maiores Insights
- **Disparidade de Gênero**: Homens representam aproximadamente 75% de todos os casos registrados.
- **Padrões de Idade**: As taxas mais altas são observadas nos grupos etários de 35-54 e 55-74 anos.
- **Tendências Geográficas**: Países do Leste Europeu e da antiga União Soviética apresentam taxas consistentemente mais altas.
- **Análise Temporal**: Os números permanecem persistentemente altos, apesar das flutuações anuais.

### Análise Geográfica
- Mapas mundiais interativos mostrando o total de casos e as taxas por 100.000 habitantes.
- A clusterização de países revela três grupos distintos com base na população e nos padrões de suicídio.
- Padrões regionais sugerem fortes influências socioeconômicas e culturais.

## Tecnologias Utilizadas

### Análise de Dados
- Python, Pandas, NumPy

### Visualização
- Matplotlib, Seaborn, Plotly

### Aprendizado de Máquina
- Scikit-learn (K-Means, StandardScaler)

### Geoespacial
- Geopandas, Folium

### Notebook
- Google Colab, Jupyter

## Estrutura do Projeto
```
who-suicide-analysis/
├── who_new.py       # Notebook principal da análise
├── requirements.txt # Dependências do Python
├── README.md        # Documentação do projeto
├── .gitignore       # Regras do Git ignore
└── LICENSE          # Licença MIT
```

## Início Rápido

### 1. Clone o repositório
```bash
git clone https://github.com/Cyb3r-Cairo/who-suicide-analysis.git
cd who-suicide-analysis
```

### 2. Instale as dependências
```bash
pip install -r requirements.txt
```

### 3. Execute a análise
```bash
jupyter notebook who_new.py
```

## Informações do Conjunto de Dados

**Fonte:** Organização Mundial da Saúde (OMS )

**Período:** 1979-2016 (37 anos)

**Países:** 141 nações

**Variáveis Principais:** País, ano, sexo, idade, número de suicídios, população

## Métodos Analíticos

### Pré-processamento de Dados
- Padronização dos nomes dos países
- Análise de valores ausentes (7% de dados ausentes)
- Conversão e validação de tipos de dados

### Análise Estatística
- Estatísticas descritivas e análise de tendências
- Comparações de grupos (gênero, idade, geográfico)
- Cálculos de taxas por 100.000 habitantes

### Aprendizado de Máquina
- **Clusterização K-Means:** Agrupamento de países em 3 clusters com base na população e nos padrões de suicídio.
- **Escalonamento de Features:** StandardScaler para comparações normalizadas.

### Técnicas de Visualização
- Mapas coropléticos interativos (Plotly)
- Análise de séries temporais com linhas de tendência
- Detalhamentos demográficos (gráficos de barras, gráficos de linha)
- Gráficos de dispersão para análise de clusters

## Resultados e Aplicações

### Implicações para a Saúde Pública
- Programas de prevenção direcionados para demografias de alto risco
- Recomendações de políticas baseadas em evidências
- Otimização da alocação de recursos

### Valor para Pesquisa
- Base para estudos comparativos
- Metodologia para análises semelhantes de saúde pública
- Dados abertos para pesquisa acadêmica

## Como Contribuir
Aceitamos contribuições! Por favor:

1. Faça um Fork do repositório
2. Crie uma branch de feature (`git checkout -b feature/AmazingFeature`)
3. Faça o commit de suas alterações (`git commit -m 'Add some AmazingFeature'`)
4. Faça o push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo `LICENSE` para mais detalhes.

## Agradecimentos
- Organização Mundial da Saúde por disponibilizar os dados
- Comunidade de ciência de dados Python por suas excelentes bibliotecas
- Google Colab pelos recursos computacionais
