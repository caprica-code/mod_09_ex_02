# 📊 Análise Socioeconômica dos Municípios de Rondônia

Este projeto realiza uma análise exploratória sobre indicadores socioeconômicos dos municípios de Rondônia, utilizando dados como PIB, IDH e IFDM, além de dados de nascimentos extraídos do SINASC.

## ✅ Objetivos

- Classificar municípios em faixas de desenvolvimento socioeconômico.
- Agrupar e analisar informações por faixas de PIB, IDH e IFDM.
- Visualizar distribuições utilizando gráficos de barras coloridos.
- Explorar possíveis correlações entre indicadores.

## 🗂️ Estrutura do Projeto

- **`dicionarios.py`**: Código de criação dos dicionários com faixas de IDH, IFDM e PIB.
- **`analise.py`**: Códigos para mapear os municípios, realizar agrupamentos (`groupby`) e gerar estatísticas descritivas.
- **`visualizacoes.py`**: Criação de gráficos de barras para as faixas de desenvolvimento.
- **`README.md`**: Documentação do projeto.

## 🔍 Metodologia

1. **Coleta de dados**:
   - Dados do PIB, IDH e IFDM extraídos da Wikipedia.
   - Dados de nascimentos obtidos do SINASC.

2. **Pré-processamento**:
   - Criação de dicionários para categorizar municípios em faixas de desenvolvimento.
   - Mapeamento das faixas para cada município.

3. **Análise**:
   - Uso de `groupby` para gerar estatísticas: média, mediana, mínimo, máximo, desvio padrão e variância.
   - Análise cruzada entre as variáveis socioeconômicas.

4. **Visualização**:
   - Gráficos de barras com `Seaborn` e `Matplotlib`.
   - Correção de `FutureWarnings` conforme novas práticas recomendadas.

## 📈 Resultados

- Gráficos mostram a distribuição dos municípios de Rondônia conforme PIB, IDH e IFDM.
- Foi possível observar como esses indicadores variam entre as regiões.
- Insights sobre como desenvolvimento socioeconômico se relaciona com dados de saúde pública (idade e escolaridade materna).

## 📦 Tecnologias Utilizadas

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook


## 📚 Referências

- [Lista de municípios de Rondônia por PIB - Wikipedia](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_de_Rond%C3%B4nia_por_PIB)
- [Lista de municípios de Rondônia por IDH - Wikipedia](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_de_Rond%C3%B4nia_por_IDH-M)
- [Lista de municípios de Rondônia por IFDM - Wikipedia](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_de_Rond%C3%B4nia_por_IFDM)
- [SINASC - Sistema de Informações sobre Nascidos Vivos](https://datasus.saude.gov.br/nascidos-vivos/)

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
