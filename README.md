# Análise de Dados de Física de Altas Energias

Este repositório contém o código desenvolvido para a análise de dados de colisões (canal $e^\pm\mu^\mp$), processando arquivos `.root` através do pacote `uproot`, organizando as informações com `pandas` e gerando gráficos padronizados com `matplotlib`.

## Funcionalidades do Código
- **Estilização de Gráficos:** Funções auxiliares para configurar eixos, grades e legendas (`style` e `labels`).
- **Leitura de Dados:** Abertura de arquivos ROOT reais (`Data_MuonEG`) e simulações de Monte Carlo (`DYJetsToLL`, `TTTo2L2Nu`, `WWTo2L2Nu`, `ZZTo2L2Nu`).
- **Normalização por Luminosidade:** Cálculo de pesos de eventos (`evtWeight`) baseados na seção de choque e na luminosidade integrada ($16393.3805 \text{ pb}^{-1}$).
- **Gráficos de Eficiência:** Processamento e verificação de eficiências de *trigger*.

## Tecnologias Utilizadas
- Python
- Pandas / NumPy
- Uproot
- Matplotlib
