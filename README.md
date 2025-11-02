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

A análise da página principal, referente ao período de 01/01/2025 a 27/12/2025[cite: 3], destaca os seguintes pontos:

**Indicadores Principais (Cards):**
* **Receita Total:** R$ 7.961 
* **Total de Viagens:** 1.000 
* **Usuários Únicos:** 612 

**Visualizações:**
1.  **Receita X Viagens (Gráfico Combinado):**     * Monitora a tendência de receita (linha) e o volume de viagens (colunas) ao longo dos meses.
    * Permite identificar rapidamente a sazonalidade e a correlação entre o faturamento e o uso. Por exemplo, janeiro teve o maior pico de receita (R$853,62) e o maior número de viagens (108).

2.  **Distribuição por Gênero (Gráfico de Rosca):** 
    * Mostra a segmentação dos usuários.
    * Os dados indicam uma distribuição equilibrada: Feminino (34,7%) , Masculino (33,9%) e Outro (31,4%).

3.  **Viagens por Tipo de Plano (Gráfico de Barras):** 
    * Compara o volume de viagens entre os diferentes tipos de assinatura (Avulso, Mensal, Trimestral, etc.).
    * Essencial para entender quais planos são mais populares e direcionar estratégias de marketing e retenção.

4.  **Top 5 Pontos de Partidas (Gráfico de Barras):** 
    * Identifica os locais com maior número de viagens iniciadas.
    * Locais como "Centro Cívico" , "Centro"  e "Avenida Paulista"  estão entre os mais movimentados, fornecendo insights valiosos para a alocação da frota.

### Filtros Interativos
O relatório permite a filtragem dinâmica por:
* **Período:** Seleção de intervalo de datas.
* **Tipo de Plano:** Análise por planos Avulso, Mensal, Semestral, Trimestral e Anual.

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
