# VIX - Análise Estatística do "Índice do Medo"

Uma análise estatística do **CBOE Volatility Index (VIX)**, conhecido como o "índice do medo", que mede a volatilidade implícita do S&P 500 com base em opções.

---

## Descrição do Projeto

Este projeto realiza as seguintes etapas:
1. **Obtenção de Dados**: Utiliza dados históricos do VIX baixados do FRED (Federal Reserve Economic Data).
2. **Divisão por Data**: Divide o dataset em arquivos CSV separados para cada dia usando Pandas e o módulo `os`.
3. **Recombinação**: Reúne os arquivos em um único dataframe para análise.
4. **Análise de Risco**: Calcula métricas como volatilidade móvel, média móvel e identifica períodos de alto risco (VIX > 30).
5. **Visualizações**: Produz gráficos informativos com Matplotlib e Seaborn, incluindo séries temporais, histogramas e heatmaps.

O objetivo é explorar o comportamento do VIX como um indicador de risco de mercado, identificar períodos de crise e entender padrões históricos.

---
