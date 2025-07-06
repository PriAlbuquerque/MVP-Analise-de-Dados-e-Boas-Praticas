# MVP-Analise-de-Dados-e-Boas-Praticas
Evolução da Produção Científica Brasileira em Medicina (2005–2021): Análise do Papel da Colaboração Internacional no Impacto da Pesquisa

Este projeto tem como objetivo explorar, limpar e organizar um conjunto de metadados de publicações científicas indexadas na base Scopus, com foco na produção brasileira na área da Medicina. Os dados serão utilizados como base para análises mais avançadas em etapas futuras (como modelagem preditiva).

🔍 Objetivo
Entender padrões de autoria, impacto e colaboração em publicações científicas.

Preparar e enriquecer o conjunto de dados com variáveis derivadas, como:

Presença de colaboração internacional.

Faixas de número de autores.

Executar boas práticas de pré-processamento de dados, removendo inconsistências e tratando valores ausentes.

🧾 Dataset
Fonte: Dump de metadados da Scopus via OpenAlex

Escopo: Publicações com pelo menos um autor afiliado ao Brasil na área da Medicina

Período: Sem restrição de data, com foco em artigos publicados até 2023

Formato: .csv, aproximadamente 250 mil registros

📂 Acesse o dataset completo:
📎 Link para o Google Drive: https://docs.google.com/spreadsheets/d/1BxnTmOhfT8UmZll0BQnQa8YM6zOqlvaP/edit?usp=drive_link&ouid=114667940732343995278&rtpof=true&sd=true

🛠️ Principais Etapas
Carregamento dos dados

Diagnóstico de valores ausentes

Limpeza e tratamento por tipo de variável

Engenharia de atributos

international_collaboration (binária)

faixa_autores (categórica)

Análises descritivas e visualizações

Pré-modelagem com regressões simples

