# 🎮 Pokémon Analytics

Projeto de **Análise de Dados desenvolvido como trabalho de conclusão do certificado Google Data Analytics**, realizado através do **Coursera**.

O projeto utiliza uma base de dados contendo informações sobre Pokémon para investigar a evolução de suas características ao longo das diferentes gerações da franquia.

A escolha do tema foi proposital: entre diferentes possibilidades de datasets, optei por trabalhar com **Pokémon**, um assunto sobre o qual já possuo algum conhecimento. Dessa forma, em vez de gastar o esforço tentando compreender um domínio completamente desconhecido, pude concentrar o projeto naquilo que realmente queria praticar: **exploração, tratamento, análise e interpretação de dados**.

O projeto foi desenvolvido utilizando **Python para análise exploratória** e **Power BI para construção do dashboard e visualização dos resultados**.

---

## 📌 Sobre o projeto

Este projeto foi desenvolvido como o **TCC do certificado Google Data Analytics**, buscando aplicar na prática conceitos aprendidos durante o curso.

A análise parte de uma base contendo informações gerais dos Pokémon, principalmente suas estatísticas (*Stats*), classificações e características relacionadas às diferentes gerações.

Apesar de o tema ser Pokémon, o objetivo principal não foi simplesmente descobrir "qual Pokémon é mais forte". A ideia foi utilizar os dados para investigar **como o nível de poder dos Pokémon se comportou ao longo da evolução da franquia**.

A análise teve como foco principal:

* Estatísticas dos Pokémon
* **BST (Base Stat Total)**
* HP
* Attack
* Defense
* Special Attack
* Special Defense
* Speed
* Tipo dos Pokémon
* Geração
* Pokémon Lendários
* Pokémon Míticos
* Ultra Beasts
* Taxa de captura
* Evolução das estatísticas ao longo das gerações

---

## 🎯 Pergunta da análise

A principal pergunta que guiou o projeto foi:

> **O nível de poder dos Pokémon influencia diretamente sua evolução ao longo das gerações?**

Para investigar essa questão, o **BST (Base Stat Total)** foi utilizado como uma das principais métricas para representar o nível geral de atributos de cada Pokémon.

A partir disso, foram realizadas comparações entre gerações, tipos e classificações especiais para identificar padrões no crescimento das estatísticas.

A ideia foi observar se os Pokémon introduzidos nas gerações mais recentes apresentam, em média, valores maiores de atributos quando comparados aos Pokémon das primeiras gerações.

---

## 🔎 Abordagem da análise

O projeto foi dividido em duas etapas principais:

### 🐍 Etapa 1 — Análise com Python

O **Jupyter Notebook** foi utilizado para realizar a exploração e análise dos dados.

Nessa etapa foram realizadas operações de:

* Importação e exploração da base
* Verificação das informações disponíveis
* Tratamento e preparação dos dados
* Agrupamento por geração
* Agrupamento por tipo
* Comparação de estatísticas
* Cálculo de médias
* Análise de BST
* Análise de Pokémon especiais
* Análise de taxa de captura
* Criação de visualizações

O objetivo dessa etapa foi encontrar padrões e relações que posteriormente poderiam ser apresentados de maneira mais objetiva no dashboard.

### 📊 Etapa 2 — Dashboard no Power BI

Após a exploração dos dados, os resultados foram organizados em um dashboard no **Power BI**.

O dashboard permite explorar diferentes características da base e comparar o comportamento dos Pokémon entre gerações.

Entre os principais pontos apresentados estão:

* Distribuição dos Pokémon por geração
* Evolução do BST médio
* Comparação das principais estatísticas
* Distribuição por tipo
* Pokémon Lendários, Míticos e Ultra Beasts
* Taxa de captura
* Comparações entre diferentes gerações

---

## 📊 Principais análises

### ⚔️ Estatísticas dos Pokémon

A análise começou pelas estatísticas individuais dos Pokémon.

Foram consideradas as principais características utilizadas para representar seus atributos:

* **HP**
* **Attack**
* **Defense**
* **Sp. Attack**
* **Sp. Defense**
* **Speed**
* **BST**

O **BST (Base Stat Total)** recebeu atenção especial por permitir uma comparação geral entre Pokémon utilizando a soma de seus atributos base.

---

### 🧬 Evolução por geração

Uma das principais análises do projeto foi observar como as estatísticas dos Pokémon mudaram ao longo das gerações.

Foram comparadas as médias de BST entre as diferentes gerações para verificar se existia uma tendência de aumento no nível geral dos Pokémon.

Essa análise permitiu observar uma diferença significativa entre as primeiras gerações e as gerações posteriores.

As três primeiras gerações apresentam médias de BST inferiores às gerações seguintes, enquanto a partir da **Geração 4** os valores passam a apresentar um nível consideravelmente mais elevado e relativamente mais estável até a **Geração 9**.

---

### ⭐ Pokémon especiais

A análise também considerou classificações especiais dentro da franquia:

* Pokémon Lendários
* Pokémon Míticos
* Ultra Beasts

Esses grupos foram comparados principalmente considerando seus valores de BST e sua presença ao longo das gerações.

Um dos pontos observados foi que os **Pokémon Lendários continuam apresentando os maiores valores de BST**, mesmo após a introdução dos Pokémon Míticos e das Ultra Beasts.

---

### 🌌 Geração 7 e as Ultra Beasts

A **Geração 7** apresentou uma característica particularmente interessante para a análise.

Além dos Pokémon tradicionais da geração, foram introduzidas as **Ultra Beasts**, aumentando a presença de Pokémon classificados como especiais dentro da base.

Isso fez com que a geração apresentasse uma concentração relevante de Pokémon com estatísticas elevadas quando comparada a outras gerações.

---

### 🎯 Taxa de captura

Outra característica analisada foi a **taxa de captura** dos Pokémon.

A comparação permitiu observar diferenças entre Pokémon comuns e classificações especiais.

Um dos padrões encontrados foi que Pokémon Míticos, como **Mew e Celebi**, apresentam uma dificuldade de obtenção diferente daquela observada para parte dos Pokémon Lendários e Ultra Beasts.

Essa análise adicionou uma perspectiva diferente ao projeto, relacionando **poder e disponibilidade** dentro da base.

---

## 💡 Principais insights

A análise permitiu chegar a alguns dos principais insights do projeto:

### 1. 🏆 Pokémon Lendários continuam no topo

Mesmo após a introdução de **Pokémon Míticos e Ultra Beasts**, os Pokémon Lendários continuam apresentando os maiores valores de **BST** dentro das classificações especiais analisadas.

---

### 2. 🌌 A Geração 7 trouxe uma concentração maior de Pokémon especiais

A introdução das **Ultra Beasts** na Geração 7 aumentou a quantidade de Pokémon classificados como especiais e com estatísticas elevadas nessa geração.

---

### 3. 📈 O poder médio aumentou ao longo das gerações

Os dados indicam um aumento expressivo no **BST médio** quando comparamos as primeiras gerações com as gerações posteriores.

As três primeiras gerações apresentam valores mais baixos, enquanto da **Geração 4 até a Geração 9** o BST médio permanece em um patamar mais elevado e relativamente nivelado.

Isso indica que o aumento do poder médio não ocorreu de maneira completamente linear, mas houve uma mudança clara de patamar entre as primeiras gerações e as seguintes.

---

### 4. 🎯 Nem todo Pokémon especial é igualmente difícil de encontrar

A análise da taxa de captura mostrou diferenças interessantes entre as classificações especiais.

Pokémon Míticos como **Mew e Celebi** apresentam taxas que indicam maior dificuldade de captura quando comparados às Ultra Beasts e a parte dos Pokémon Lendários analisados.

Isso mostra que **BST e dificuldade de obtenção são características diferentes**, não sendo possível assumir que um Pokémon mais poderoso necessariamente será mais difícil de encontrar.

---

## 📊 Dashboard

O resultado final da análise foi transformado em um dashboard no **Power BI**, reunindo os principais indicadores e comparações encontradas durante a exploração dos dados.

O objetivo do dashboard é permitir uma visualização mais rápida da evolução dos Pokémon ao longo das gerações, além de possibilitar comparações entre diferentes atributos e classificações.

![Dashboard](images/dashboard.png)

> *Adicione aqui as imagens finais do dashboard conforme a estrutura do repositório.*

---

## 🐍 Análise com Python

A análise exploratória foi desenvolvida utilizando **Python através de um Jupyter Notebook**.

Entre os principais conceitos utilizados estão:

```python
read_csv()
head()
shape
info()
describe()
isnull()
groupby()
agg()
sort_values()
nlargest()
nsmallest()
reset_index()
pivot_table()
loc[]
query()
nunique()
```

Também foram utilizadas operações de transformação e agregação para comparar as estatísticas dos Pokémon entre diferentes grupos.

### Principais bibliotecas

* **Pandas** → Manipulação e análise dos dados
* **NumPy** → Operações numéricas
* **Matplotlib** → Visualização de dados
* **Seaborn** → Visualizações estatísticas
* **Jupyter Notebook** → Desenvolvimento da análise exploratória

---

## 🔄 Fluxo da análise

O projeto seguiu um fluxo baseado nas etapas estudadas durante o certificado de **Google Data Analytics**:

```text
Dataset Pokémon
       │
       ▼
Exploração dos dados
       │
       ▼
Preparação / Tratamento
       │
       ▼
Análise exploratória
       │
       ▼
Python + Pandas
       │
       ▼
Identificação de padrões
       │
       ▼
Visualização dos resultados
       │
       ▼
Power BI
       │
       ▼
Dashboard + Insights
```

---

## 🧠 Principais aprendizados

O projeto foi desenvolvido principalmente como uma forma de colocar em prática os conhecimentos adquiridos durante o certificado **Google Data Analytics**.

Mais do que aprender novas funções de Python ou construir um dashboard no Power BI, o projeto permitiu praticar o processo completo de transformar uma base de dados em uma análise.

Alguns dos principais aprendizados foram:

* Explorar uma base antes de começar a análise
* Identificar quais perguntas podem ser respondidas pelos dados
* Escolher métricas adequadas para cada problema
* Utilizar agrupamentos para encontrar padrões
* Comparar médias e distribuições
* Criar visualizações para facilitar a interpretação
* Diferenciar correlação de causalidade
* Transformar resultados técnicos em insights compreensíveis
* Utilizar ferramentas diferentes dentro do mesmo processo analítico

Um dos pontos mais importantes foi perceber que **conhecer o contexto do dado ajuda, mas não substitui a análise**.

Escolher Pokémon como tema facilitou a compreensão das informações e das classificações presentes na base, permitindo que o foco do projeto estivesse no processo de análise e na interpretação dos resultados.

---

## 🛠️ Tecnologias utilizadas

### 📊 Análise de Dados

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### 📈 Visualização

* Microsoft Power BI

### 🗃️ Dados

* Dataset de Pokémon
* CSV

### 🔧 Ferramentas

* Visual Studio Code
* Jupyter Notebook
* Power BI
* Git
* GitHub

---

## 📂 Estrutura do projeto

```text
Pokemon-Analytics/
│
├── data/
│   └── pokemon.csv
│
├── python/
│   └── Pokemon_Analytics.ipynb
│
├── powerbi/
│   └── Pokemon_Analytics.pbix
│
├── images/
│   ├── dashboard.png
│   ├── dashboard_2.png
│   └── ...
│
├── README.md
└── requirements.txt
```

**Organização:**

* `data/` → dataset utilizado na análise
* `python/` → Jupyter Notebook contendo a análise exploratória
* `powerbi/` → arquivo do dashboard desenvolvido no Power BI
* `images/` → imagens utilizadas na documentação
* `README.md` → documentação do projeto
* `requirements.txt` → dependências utilizadas na análise Python

---

## 📌 Conclusão

A análise buscou investigar se o nível de poder dos Pokémon apresentou evolução ao longo das gerações, utilizando principalmente o **BST médio** como métrica de comparação.

Os dados analisados mostram uma diferença clara entre as primeiras gerações e as gerações posteriores, com o BST médio apresentando um aumento significativo a partir da Geração 4 e permanecendo em um patamar mais elevado até a Geração 9.

A análise também mostrou que a evolução da franquia trouxe novas classificações e grupos de Pokémon, como os **Pokémon Míticos e as Ultra Beasts**, sem que isso alterasse o fato de que os Pokémon Lendários continuam apresentando os maiores valores de BST entre os grupos especiais analisados.

Por outro lado, a análise da taxa de captura mostrou que **poder e dificuldade de obtenção não caminham necessariamente juntos**, criando uma perspectiva adicional sobre os dados.

Mais do que responder uma pergunta sobre Pokémon, o projeto serviu como aplicação prática do processo de **Data Analytics**, desde a exploração da base até a criação de visualizações e obtenção de insights.

---

## 🚀 Próximos passos

Possíveis evoluções para o projeto:

* 📊 Expandir o dashboard com novas métricas
* 🧬 Analisar as linhas evolutivas dos Pokémon
* ⚔️ Comparar tipos considerando diferentes estatísticas
* 📈 Criar análises estatísticas mais avançadas
* 🗃️ Integrar os dados com um banco de dados
* 🔄 Automatizar a atualização da base
* 🌐 Criar uma versão web interativa do dashboard
* 📡 Integrar dados de APIs relacionadas a Pokémon
* 🤖 Explorar modelos preditivos utilizando as características dos Pokémon

---

## 👨‍💻 Autor

**Julio Guimarães**

Projeto desenvolvido como trabalho de conclusão do **Google Data Analytics Certificate**, com o objetivo de aplicar conhecimentos de análise, exploração e visualização de dados em um projeto prático.

* 💻 GitHub: [jullyoo](https://github.com/Jullyoo)
* 💼 LinkedIn: [LinkedIn](https://www.linkedin.com/in/j-guimaraes/)
* 🌐 Portfólio: [Julyo.dev](https://julyo-dev.vercel.app)

---

> 🎓 "Eu ainda não sei tudo, e é por isso que continuo viajando!"— Ash Ketchum (Pokemon)*
