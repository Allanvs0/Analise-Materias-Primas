# 📊 Análise de Matérias-Primas Agrícolas

Este projeto foi desenvolvido no **Google Colab** como prática de **Análise Exploratória de Dados (EDA)**.  
O objetivo foi tratar, explorar e visualizar um conjunto de dados de matérias-primas agrícolas, respondendo perguntas sobre **faixa de preços, variação percentual e correlações** entre commodities.

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

## 📊 Exemplos de gráficos

### 🔥 Mapa de calor de correlação
![Heatmap](img/heatmap.png)

### 📈 Evolução do preço de commodities
![Linha](img/lineplot.png)

### 📦 Faixa de preço das matérias-primas de baixo valor
![Boxplots](img/boxplots.png)

> ⚠️ Para visualizar os gráficos no README, salve-os no Colab usando `plt.savefig("img/nome.png")` e suba a pasta `img/` junto no repositório.

---

## 🚀 Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/Allanvs0/analise-materias-primas.git

2. Abra o arquivo analise_materias_primas.ipynb no Google Colab ou Jupyter Notebook.

3. Instale as dependências (caso rode localmente):

4. pip install pandas numpy matplotlib seaborn


Execute as células em ordem para reproduzir a análise.

📌 Conclusões

Algumas commodities apresentam preços consistentemente baixos, enquanto outras têm preços altos e mais instáveis.

A variação percentual mostrou quais matérias-primas sofrem mudanças bruscas e quais são mais estáveis.

O mapa de calor revelou correlações interessantes entre os preços de diferentes commodities.

Este estudo pode ser expandido para previsões de preços e análises comparativas mais profundas.
