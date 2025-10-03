# 📊 Análise de Matérias-Primas Agrícolas

Este projeto foi desenvolvido no **Google Colab** como prática de **Análise Exploratória de Dados (EDA)**.  
O objetivo foi tratar, explorar e visualizar um conjunto de dados de matérias-primas agrícolas, respondendo perguntas sobre **faixa de preços, variação percentual e correlações** entre commodities.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Allanvs0/Analise-Materias-Primas/blob/main/Analise-Materias-Primas/Materiais_de_agricultura.ipynb)

---

## 🛠️ Tecnologias utilizadas
- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📂 Estrutura do projeto
analise-materias-primas/<br>
├── data/<br>
│ └── agricultural_raw_material.csv # Base de dados utilizada<br>
├── analise-materias-primas/<br>
│ └── analise_materias_primas.ipynb # Notebook principal<br>
└── README.md # Documentação


---

## 🔍 Etapas da análise

1. **Importação e inspeção dos dados**
   - Leitura do arquivo CSV em um `DataFrame`.
   - Verificação de colunas, tipos e valores ausentes.

2. **Tratamento dos dados**
   - Remoção de símbolos como `%`, `,`, `-`.
   - Substituição de valores inválidos (`NaN`).
   - Conversão de colunas numéricas para `float`.
   - Padronização da coluna de datas (`Month`) e definição como índice.

3. **Exploração e Visualização**
   - **Mapa de calor** de correlação entre preços.
   - **Histogramas** da variação percentual.
   - **Gráficos de linha** da evolução de preços.
   - **Boxplots** das faixas de preço.
   - **Scatterplots** mostrando mudanças bruscas.

4. **Respostas às perguntas**
   - **P1:** Qual a variação normal do preço de cada matéria-prima?  
   - **P2:** Qual a matéria-prima com menor preço ao longo dos anos?  
   - **P3:** Qual possui maior e menor variação percentual de preço?  
   - **P4:** Quais matérias-primas tiveram mudanças drásticas de preço?  
   - **P5:** Qual a faixa de preço das matérias-primas de baixo valor?  

---

## 🚀 Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/Allanvs0/analise-materias-primas.git

2. Abra o arquivo analise_materias_primas.ipynb no Google Colab ou Jupyter Notebook.

3. Instale as dependências (caso rode localmente):

4. pip install pandas numpy matplotlib seaborn

Execute as células em ordem para reproduzir a análise.

---

📌 Conclusões

Algumas commodities apresentam preços consistentemente baixos, enquanto outras têm preços altos e mais instáveis.

A variação percentual mostrou quais matérias-primas sofrem mudanças bruscas e quais são mais estáveis.

O mapa de calor revelou correlações interessantes entre os preços de diferentes commodities.

Este estudo pode ser expandido para previsões de preços e análises comparativas mais profundas.

---
Para visualizar os gráficos interativos, abra o notebook no Google Colab
