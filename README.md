# Projeto de Análise de Dados: Dashboard Verde Vias (Power BI)

Este repositório contém um projeto de Business Intelligence desenvolvido em Power BI para a **Verde Vias Mobilidade Sustentável**, uma empresa fictícia do setor de micro-mobilidade (patinetes elétricos).

## 🚀 O Desafio de Negócio

A Verde Vias precisava de uma solução para centralizar e analisar seus dados de viagens. O objetivo principal era transformar dados transacionais brutos (de uma planilha Excel) em insights acionáveis para a tomada de decisão executiva.

Os principais objetivos do cliente (Verde Vias) eram:
* Monitorar a performance financeira (Receita, Ticket Médio).
* Entender o volume de uso (Total de Viagens, Usuários Únicos).
* Identificar padrões de comportamento dos usuários (Gênero, Tipo de Plano).
* Otimizar a logística operacional (identificando os Pontos de Partida mais populares).

## 📊 O Dashboard

O dashboard foi construído para fornecer uma visão clara e interativa dos principais indicadores de desempenho da empresa. A página principal, "Visão Executiva", concentra-se nos resultados gerais.

 
### KPIs e Análises da Página Principal

[cite_start]A análise da página principal, referente ao período de 01/01/2025 a 27/12/2025[cite: 3], destaca os seguintes pontos:

**Indicadores Principais (Cards):**
* [cite_start]**Receita Total:** R$ 7.961 [cite: 1]
* [cite_start]**Total de Viagens:** 1.000 [cite: 4]
* [cite_start]**Usuários Únicos:** 612 [cite: 5]

**Visualizações:**
1.  [cite_start]**Receita X Viagens (Gráfico Combinado):** [cite: 6, 11]
    * Monitora a tendência de receita (linha) e o volume de viagens (colunas) ao longo dos meses.
    * Permite identificar rapidamente a sazonalidade e a correlação entre o faturamento e o uso. [cite_start]Por exemplo, janeiro teve o maior pico de receita (R$853,62) [cite: 23] [cite_start]e o maior número de viagens (108)[cite: 16].

2.  [cite_start]**Distribuição por Gênero (Gráfico de Rosca):** [cite: 33]
    * Mostra a segmentação dos usuários.
    * [cite_start]Os dados indicam uma distribuição equilibrada: Feminino (34,7%) [cite: 51][cite_start], Masculino (33,9%) [cite: 32] [cite_start]e Outro (31,4%)[cite: 34].

3.  [cite_start]**Viagens por Tipo de Plano (Gráfico de Barras):** [cite: 7]
    * [cite_start]Compara o volume de viagens entre os diferentes tipos de assinatura (Avulso [cite: 8][cite_start], Mensal [cite: 47][cite_start], Trimestral[cite: 10], etc.).
    * Essencial para entender quais planos são mais populares e direcionar estratégias de marketing e retenção.

4.  [cite_start]**Top 5 Pontos de Partidas (Gráfico de Barras):** [cite: 49]
    * Identifica os locais com maior número de viagens iniciadas.
    * [cite_start]Locais como "Centro Cívico" [cite: 50][cite_start], "Centro" [cite: 52] [cite_start]e "Avenida Paulista" [cite: 54] estão entre os mais movimentados, fornecendo insights valiosos para a alocação da frota.

### Filtros Interativos
O relatório permite a filtragem dinâmica por:
* [cite_start]**Período:** Seleção de intervalo de datas[cite: 2].
* [cite_start]**Tipo de Plano:** Análise por planos Avulso, Mensal, Semestral, Trimestral e Anual[cite: 8, 47, 48, 10, 45].

## 🛠️ Ferramentas e Tecnologias

* **Microsoft Power BI:** Ferramenta principal para ETL (Power Query), modelagem de dados, cálculos DAX e visualização.
* **DAX (Data Analysis Expressions):** Utilizado para criar as medidas complexas (ex: Receita Total, Ticket Médio) e colunas calculadas (ex: Nome do Mês, Faixa Etária).
* **Excel:** Utilizado como fonte de dados (fictícia) para o projeto.

## 📁 Conteúdo do Repositório

* `/VerdeVias.pbix`: O arquivo principal do Power BI contendo o dashboard.
* `/Dados/VerdeVias_Dados.xlsx`: A fonte de dados fictícia utilizada no projeto (se aplicável).
* `/Imagens/`: Contém imagens e prévias do dashboard.
* `README.md`: Este arquivo.

## 👨‍💻 Autor

Hoalys Anjos
https://www.linkedin.com/in/hoalysanjos-analista/
