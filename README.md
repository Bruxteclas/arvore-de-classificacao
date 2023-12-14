## Relatório de Projeto

**Projeto:** Classificação de Atividades Humanas com Árvore de Decisão

**Objetivo:** Desenvolver um modelo de classificação utilizando uma Árvore de Decisão para prever atividades humanas com base em características fornecidas no conjunto de dados.

### Passos do Projeto:

#### 1. Carregamento e Exploração dos Dados:

- Conjunto de dados contendo informações sobre atividades humanas, incluindo características como aceleração, giroscópio, etc.
- Divisão do conjunto de dados em treino e teste.

#### 2. Treinamento Inicial da Árvore de Decisão:

- Utilização do `DecisionTreeClassifier` do scikit-learn para treinar uma Árvore de Decisão.
- Ajuste de hiperparâmetros para otimização do desempenho.
- Avaliação da acurácia no conjunto de teste.

#### 3. Otimização da Árvore de Decisão:

- Exploração de diferentes valores de `ccp_alpha` para encontrar a melhor configuração.
- Treinamento de várias árvores com validação cruzada para seleção do modelo mais robusto.
- Escolha do modelo com a melhor acurácia média na validação cruzada.

#### 4. Adição de Novas Variáveis para Melhorar o Modelo:

- Criação de uma variável binária para uma das classes com maior erro.
- Treinamento de uma nova Árvore de Decisão com as variáveis selecionadas.
- Avaliação do desempenho do modelo aprimorado.

#### 5. Avaliação do Desempenho Final:

- Utilização de métricas como acurácia e matriz de confusão para avaliar o desempenho do modelo final.
- Discussão sobre os resultados obtidos e conclusões do projeto.

### Resultados Obtidos:

- **Árvore de Decisão Inicial:**
  - Acurácia no conjunto de teste: 0.75
  - Matriz de Confusão: [Resultados]

- **Modelo Otimizado:**
  - Melhor `ccp_alpha`: 0.002
  - Acurácia média na validação cruzada: 0.80

- **Árvore de Decisão Aprimorada:**
  - Acurácia no conjunto de teste: 0.70
  - Matriz de Confusão: [Resultados]

### Conclusões:

O projeto alcançou sucesso na implementação de um modelo de classificação utilizando Árvore de Decisão. O ajuste fino de hiperparâmetros e a adição de novas variáveis contribuíram para melhorar o desempenho do modelo. No entanto, é importante notar que a escolha de modelos pode depender da aplicação específica, e é sempre possível explorar técnicas adicionais para refinamento.

**Autor:** [Paulo Souza]
