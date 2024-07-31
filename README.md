# Dashboard de Logística com Power BI

Bem-vindo ao repositório do **Dashboard de Logística**! Este projeto foi desenvolvido para uma empresa fictícia de logística utilizando **Power BI**. Durante o desenvolvimento, explorei funcionalidades do **Power Query** e criei visualizações impactantes para analisar métricas e indicadores essenciais para o setor de logística.

## 📊 Projeto

O objetivo deste projeto é oferecer uma visão clara e detalhada das operações logísticas, utilizando um dashboard interativo que facilita a tomada de decisões estratégicas.

### 🗂️ Estrutura dos Dados

O dashboard foi construído a partir de uma planilha contendo as seguintes colunas:

- **Viagem**
- **Data Pedido**
- **Data Entrega**
- **Prazo Entrega**
- **Endereço**
- **Marca**
- **Veículo**
- **Valor do Frete Líquido**
- **KM**
- **Tempo de Entrega**
- **Status de Entrega**
- **Cidade**
- **Estado**
- **Motorista**
- **Custos**

### 🖥️ Construção do Dashboard

Utilizei um plano de fundo personalizado para criar um visual agradável e organizado, distribuindo os elementos de maneira intuitiva:

- **Parte Superior**:
  - Quatro cartões exibindo **Receita**, **Lucro**, **KM Rodados** e **Quantidade de Viagens**, cada um com ícones representativos para tornar o dashboard mais atrativo visualmente.
  - Ao lado dos cartões, foi adicionada uma segmentação de dados que permite ao usuário filtrar os resultados por **Ano** e **Mês**.
  
- **Parte Inferior**:
  - Um **Gráfico de Colunas** representando a **Quantidade de Viagens por Mês**.
  - Um **Gráfico de Indicador** que mostra a **Porcentagem de Entregas dentro do Prazo**.
  - Uma **Árvore Hierárquica** que começa com a **Receita** e detalha a contribuição de cada **Marca** e **Tipo de Veículo** para os resultados, permitindo uma análise aprofundada de como cada fator influencia o desempenho da empresa.

## 🔧 Aprendizados no Power Query

- **Manipulação de Dados**: Remoção de colunas, remoção de linhas em branco, divisão de colunas por delimitador, mesclagem de colunas, criação de colunas personalizadas, colunas com cálculo e colunas condicionais.
- **Automatização e Eficiência**: A utilização do Power Query permite uma manipulação rápida e fácil dos dados sem alterar a planilha original. Além disso, quando a planilha original é alterada, as configurações podem ser reaplicadas com apenas um clique, ideal para automatizar processos.

## 🧮 Medidas com DAX

Para uma análise mais detalhada, foram criadas medidas personalizadas utilizando fórmulas DAX, incluindo:

- **SUM**: Soma de valores.
- **AVERAGE**: Média de valores.
- **COUNT** e **COUNTROWS**: Contagem de itens.
- **CALCULATE**: Cálculo de valores com filtros específicos.

## 🛠️ Tecnologias Utilizadas

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query** (para transformação e limpeza de dados)

## 📂 Estrutura do Repositório

- `Dashboard.pbix`: Arquivo do Power BI com o dashboard completo.
- `Dados/`: Diretório com as planilhas de dados utilizadas.


