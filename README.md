# Praceando - Análise Exploratória de Parques Urbanos

## Descrição

Este repositório contém um notebook que realiza uma análise exploratória de dados sobre parques urbanos, utilizando uma base pública fornecida pelo Centro de Pesquisas Metropolitanas da USP. A análise tem como foco entender as características dos parques, com o objetivo de aprimorar as funcionalidades do aplicativo **Praceando**, que promove a descoberta e o acesso a eventos em parques e praças.

## Objetivo

O objetivo deste notebook é examinar a base de dados de parques urbanos, identificando padrões e tendências que possam contribuir para o desenvolvimento do aplicativo. Através de visualizações e estatísticas descritivas, buscamos entender a distribuição, características e gestão dos parques, fornecendo insights que ajudem a melhorar a experiência do usuário no **Praceando**.

## Descrição da Base
A base de dados analisada contém informações detalhadas sobre parques urbanos, incluindo:

- Categorias dos Parques: Classificação dos parques, como parques recreativos, parques botânicos, entre outros.
- Instância Administrativa: Identificação da entidade responsável pela gestão do parque.
- Área do Parque: Medida da área total em metros quadrados (m²) e hectares (ha), permitindo a análise do tamanho dos parques.
- Ano de Criação: Informações sobre o ano em que cada parque foi inaugurado, possibilitando análises temporais.
- Tipologia de Parque: Descrição do tipo de parque, que pode incluir parques urbanos, de conservação, entre outros.
- Através dessa base, o notebook explora as principais características dos parques, como a distribuição de áreas por categoria, a quantidade de parques por instância administrativa, e análises temporais da criação dos parques. O objetivo é entender melhor os fatores que influenciam a criação e gestão dos parques e, assim, fornecer um suporte mais preciso às funcionalidades do aplicativo.

## Tecnologias Utilizadas

- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib**: Para visualizações estáticas.
- **Plotly Express**: Para visualizações interativas e dinâmicas.

## Estrutura do Notebook

1. **Importações e Configurações**: Carrega as bibliotecas necessárias e define o estilo das visualizações.
2. **Carregamento e Visualização Inicial dos Dados**: Importa o conjunto de dados de parques urbanos e exibe as primeiras entradas.
3. **Tratamento de Dados**: Realiza o tratamento de dados ausentes, removendo ou substituindo valores conforme necessário, e garante que os tipos de dados estejam corretos.
4. **Análise Exploratória**:
   - Distribuição de áreas por categoria de parque.
   - Contagem de parques por categoria e instância administrativa.
   - Análise do tamanho médio de parques por classificação.
   - Análise da criação de parques ao longo dos anos.
   - Heatmap de correlação entre variáveis numéricas.

## Contatos

Para mais informações, entre em contato com os membros da equipe de dados:
- [Fernanda Leão](https://github.com/fernandaleaoleita)
- [Guilherme Barbosa](https://github.com/guii-barbosa)
