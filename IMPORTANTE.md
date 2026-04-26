# IMPORTANTE — Entrega 3

Antes de executar o notebook da Entrega 3, instale as dependências necessárias rodando o comando abaixo no terminal:

```bash
pip install -r requirements.txt
```

## Dependências instaladas

| Pacote | Finalidade |
|---|---|
| `numpy` / `pandas` | Manipulação de dados e séries temporais |
| `matplotlib` / `seaborn` | Visualizações e gráficos |
| `requests` | Coleta de dados via API do IBGE |
| `statsmodels` | Modelo SARIMAX |
| `pmdarima` | Seleção automática de hiperparâmetros (auto_arima) |
| `scikit-learn` | Métricas de avaliação (MAE, RMSE) |

## Observação

O notebook coleta os dados automaticamente via API pública do IBGE (tabela 8880 — PMC) ao ser executado, portanto é necessário ter conexão com a internet.
