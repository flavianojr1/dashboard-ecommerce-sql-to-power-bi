# Projeto Final - Módulo 26: Analytics para E-commerce

Este repositório contém o projeto final do módulo 26, realizado como parte do curso de Ciência de Dados da **EBAC (Escola Britânica de Artes Criativas e Tecnologia)**.

## Descrição do Projeto

O objetivo deste projeto é proporcionar experiência prática com análise e visualização de dados de um e-commerce, incluindo manipulação de dados em Python e SQL, integração com ferramentas de BI e entrega de insights de negócio.

O fluxo principal deste notebook inclui:
- Tratamento e integração de dados de transações e clientes usando SQL (SQLite).
- Padronização de campos (ex: capitalização da coluna "Card Type").
- Exportação dos dados para CSV.
- Sugestões e dicas para importar os dados e criar dashboards no Power BI ou Looker Studio.

## Tabelas Utilizadas

- **Transações:** Dados das compras realizadas (id, valor, categoria, tipo de cartão, etc).
- **Clientes:** Dados pessoais dos clientes (id, nome, gênero, cargo, estado, etc).

Essas tabelas são unidas pela chave `ID_CLIENT`, que identifica o cliente.

## Etapas do Projeto

1. **JOIN SQL:** 
   - Realização da junção entre as tabelas de clientes e transações.
   - Justificativa de escolha do JOIN: utilizado `LEFT JOIN` para garantir registro de todos os clientes, mesmo sem transações.
2. **Exportação dos Dados:** 
   - Salvamento do resultado consolidado em CSV para posterior uso nas ferramentas de BI.
3. **Visualização:**
   - Orientação para importar o CSV no Looker Studio ou Power BI.
   - Sugestões de métricas e KPIs: total de vendas, quantidade de transações, distribuição geográfica e perfil demográfico.

## Como Reproduzir

1. Execute cada célula do notebook seguindo a ordem.
2. Edite os caminhos para os arquivos CSV conforme sua estrutura local.
3. Após exportar o CSV final, utilize-o para montar seu dashboard na ferramenta de sua escolha.

## Observação

Este projeto é destinado apenas para fins educacionais no escopo do curso EBAC.