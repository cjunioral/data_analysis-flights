# ✈️ Projeto de Data Science - Análise de Fluxo Aéreo e Rotas Estratégicas
### 📘 Descrição do Projeto
Este projeto utiliza um dataset abrangente de registros de voos para realizar uma Análise Exploratória de Dados (EDA) detalhada sobre o desempenho e as tendências do transporte aéreo. O estudo se concentra em transformar dados brutos de voos em insights acionáveis sobre padrões de tráfego, popularidade de rotas e o impacto da distância.

A análise utiliza poderosas ferramentas de manipulação e visualização de dados do Python para identificar os voos mais curtos, as rotas mais lucrativas, o comportamento do passageiro e a distribuição dos voos ao longo do tempo e da distância.

### 🎯 Objetivos Centrais
O projeto visou responder a questões-chave sobre a operação e logística das rotas aéreas:

Padrões de Tráfego: Identificar e classificar os aeroportos de destino mais movimentados e as rotas mais populares em termos de número de passageiros e voos.

Segmentação de Distância: Categorizar as distâncias de voo em intervalos (bins) para analisar a participação de cada faixa de distância no total de voos e passageiros transportados.

Identificação de Nichos: Isolar voos que se encaixam em perfis específicos, como rotas curtas e com alta frequência (Distance < 300 & Flights > 10), ou voos com baixa ocupação (Seats > Passengers).

Análise Temporal: Transformar e agrupar os dados por ano e mês para visualizar a evolução do total de voos ao longo do tempo.

### 🧠 Principais Insights
A aplicação das técnicas de Data Science revelou os seguintes insights essenciais:

Dominância das Rotas de Curta e Média Distância: O gráfico de pizza da distribuição de voos por distância sugere que a maioria dos voos se concentra nas faixas de curta e média distância, sendo as rotas longas (acima de 3000 milhas) uma parcela pequena do volume total.

Concentração de Passageiros: As 10 rotas mais populares concentram uma parte significativa do tráfego total de passageiros, conforme evidenciado no Gráfico de Pizza, indicando a importância estratégica de hubs específicos e conexões de alta demanda (como as rotas envolvendo LAX, HNL, etc.).

Relação Distância vs. Passageiros: O Gráfico de Dispersão (scatter plot) entre 'Distance' e 'Passengers' é crucial para entender se as rotas mais longas transportam, proporcionalmente, mais passageiros, ou se a maior densidade de tráfego ocorre nas rotas de média distância.

Verificação de Ocupação: A filtragem por Seats > Passengers permitiu identificar rapidamente o número de voos que operaram com assentos vazios, um dado vital para a gestão de receita e capacidade.

### 🛠️ Tecnologias Utilizadas
O desenvolvimento e a execução das análises foram realizados com base nas seguintes ferramentas e bibliotecas:

Linguagem: Python – Utilizado para todo o processamento de dados, lógica condicional e análise estatística.

Manipulação de Dados: Pandas – Essencial para a limpeza (conversão de Fly Date para datetime), filtragem condicional (indexação booleana e .query()), segmentação (pd.cut()) e agregação (groupby(), .agg(), .nlargest()).

Visualização: Matplotlib – Usado para gerar gráficos diversos, incluindo Barras (para rankings), Linhas (para tendências anuais), Pizza (para proporções) e Dispersão (para correlações).

### 👨‍💻 Autor
Cícero Ramalho Júnior 

#### 🔗 LinkedIn: www.linkedin.com/in/ciceroramalhojunior
