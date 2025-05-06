# Projeto de Modelagem Preditiva com LSTM para Séries Temporais Financeiras

---

**Responsável Técnico:** João Renan S. Lopes  
**Supervisão Acadêmica:** Profa. Polyana Fonseca

---

## Objetivo

Este projeto tem como finalidade a implementação de um modelo preditivo baseado em Redes Neurais Recorrentes, especificamente Long Short-Term Memory (LSTM), aplicado a séries temporais financeiras reais. O foco está na obtenção de previsões altamente precisas, com ênfase em rigor estatístico, validação robusta e boas práticas de engenharia de modelos.

---

## Componentes do Projeto

- **Aquisição de Dados:** Coleta automática de séries históricas através da API do Yahoo Finance.
- **Pré-processamento:**
  - Suavização da série original (média móvel central)
  - Decomposição da série (componente de tendência)
  - Normalização com MinMaxScaler
- **Modelagem com LSTM:**
  - Arquitetura multi-camada otimizada
  - Camadas de Dropout ajustadas para mitigação de overfitting
  - Função de perda Huber Loss para robustez contra outliers
- **Validação e Avaliação:**
  - Divisão em conjunto de treino e teste
  - Métricas aplicadas: RMSE, MAE, R² Score
  - Visualização das previsões vs. valores reais

---

## Tecnologias Utilizadas

- Python (NumPy, Pandas, Matplotlib, Scikit-learn)
- TensorFlow / Keras
- Statsmodels
- Yahoo Finance API

---

## Resultados Esperados

Obter previsões de curto a médio prazo com alta acurácia, possibilitando a aplicação do modelo em ambientes de suporte à decisão financeira.

---

## Observações Finais

Este projeto pode ser expandido para incorporar:
- Otimização bayesiana de hiperparâmetros
- Integração com indicadores técnicos (MACD, RSI)
- Cenários de multi-séries com múltiplas entradas

---

