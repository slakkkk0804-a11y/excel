# Dashboard da Porsche com Agentes de IA

Projeto desenvolvido como entrega prática para o desafio da DIO **Criando uma Dashboard da Porsche com Agentes de IA**.

## Objetivo

Organizar, tratar e visualizar dados comerciais de forma clara, usando Excel para o dashboard e um agente de IA como apoio no processo de limpeza e preparação da base.

## Estrutura do projeto

- `Dashboard_Porsche_Agentes_IA.xlsx`: arquivo principal do dashboard em Excel.
- `resumo_mensal.csv`: resumo mensal da base demonstrativa usada para estruturar os gráficos.
- `prompt_agente.txt`: prompt sugerido para um agente de tratamento de dados.

## Dashboard

O modelo apresenta indicadores como:

- unidades vendidas;
- receita total;
- ticket médio;
- atingimento médio das metas;
- modelo com maior volume;
- evolução mensal;
- desempenho por modelo;
- receita por região;
- mix por motorização.

## Agente de IA

O fluxo de tratamento considera padronização de datas e textos, conversão de campos numéricos, identificação de duplicidades, análise de valores ausentes, validação de regras de negócio e sinalização de possíveis outliers antes da atualização do dashboard.

## Material oficial da DIO

Projeto: https://www.dio.me/es/projects/criando-agentes-de-criacao-de-dashboards-com-excel-e-claude-code

Planilha base Porsche (Sanitizada): https://hermes.dio.me/files/assets/8683bed0-cc33-4e06-bca9-04db9c31f9e2.xlsx

## Observação sobre os dados

A planilha criada nesta entrega utiliza uma **base demonstrativa fictícia** para estruturar o dashboard, porque o arquivo oficial da DIO não pôde ser baixado diretamente pelo ambiente utilizado na criação. A aba `Base_Porsche` foi organizada para poder ser substituída pela base sanitizada oficial.

Este projeto tem finalidade acadêmica e de portfólio.