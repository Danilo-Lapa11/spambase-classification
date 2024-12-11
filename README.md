# Machine Learning Classifiers Comparison

Este repositório é dedicado à primeira etapa da disciplina **Aprendizado de Máquina (IF669)** do CIn/UFPE, com o objetivo de comparar quatro classificadores de machine learning e avaliar suas métricas de validação.

## Classificadores Utilizados
1. **Árvores de Decisão**
2. **Bayesiano Ingênuo (Naïve Bayes)**
3. **Regressão Logística**
4. **K-Vizinhos Mais Próximos (KNN)**

## Metodologia

### Divisão dos Dados
- Os dados serão separados de forma **aleatória e estratificada**, proporcional ao número de exemplos de cada classe.
- Sugestão de divisão:
  - **70%** para treinamento + validação
  - **30%** para teste

### Treinamento e Validação
1. Cada classificador foi treinado sob o mesmo **conjunto de treinamento**.
2. Uso de Validação Cruzada
3. O **conjunto de teste** foi reservado exclusivamente para avaliar o desempenho final dos modelos, sem ser utilizado durante o treinamento ou ajuste de hiperparâmetros.

### Avaliação
Os modelos foram avaliados utilizando as seguintes métricas no conjunto de teste:
- **Precisão (Precision)**
- **Cobertura (Recall)**
- **F1-Score**

### Otimização
- Nosso objetivo é buscar os melhores hiperparâmetros para cada classificador, com o objetivo de maximizar as métricas de precisão, cobertura e F1-Score.

## Estrutura do Repositório
- `notebooks/`: Contém notebooks Jupyter com o código para treinamento, validação e teste dos modelos.
- `data/`: Conjunto de dados utilizado no projeto.
- `results/`: Resultados das métricas e análises comparativas.
- `documentacao.pdf`: Documentação do projeto.

## Requisitos
Certifique-se de ter os seguintes pacotes instalados:
- Python 3.12
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Para instalar as dependências, execute:
```bash
pip install -r requirements.txt
```

## Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-projeto.git
   ```
2. Execute os notebooks na pasta `notebooks/` para reproduzir os experimentos.

## Contribuições
Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

## Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais informações.

