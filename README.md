# Análise de Dados de Movimentação Portuária no Brasil

Este repositório contém uma análise de dados sobre a movimentação portuária no Brasil, utilizando dados disponibilizados pela ANTAQ (Agência Nacional de Transportes Aquaviários). O objetivo é explorar, limpar e modelar os dados para extrair insights relevantes sobre as operações portuárias.

## Fonte dos Dados
Os dados utilizados nesta análise são obtidos diretamente do site da ANTAQ, no link abaixo:
- **Link de Origem:** [https://web3.antaq.gov.br/ea/sense/download.html#pt](https://web3.antaq.gov.br/ea/sense/download.html#pt)

## Descrição do Projeto
O projeto consiste em:
1. **Coleta de Dados:** Extração dos dados brutos disponíveis no site da ANTAQ.
2. **Limpeza e Tratamento:** Remoção de duplicatas, consolidação de registros e ajustes nas colunas para garantir a consistência dos dados.
   - Exemplo: Registros duplicados de navios com o mesmo código são consolidados em uma única entrada, somando as quantidades de cargas semelhantes (como soja).
3. **Análise Exploratória:** Exploração dos dados para identificar padrões, tendências e insights sobre a movimentação portuária.
4. **Exportação dos Dados:** Geração de arquivos CSV modelados e prontos para uso em outras análises ou visualizações.

