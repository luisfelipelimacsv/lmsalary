# Análise de Salários em Relação a Experiência e Educação

Este projeto analisa como anos de experiência e nível educacional afetam os salários usando dados de um conjunto de dados de salários.

## Objetivos
- Explorar a relação entre salário, experiência e educação
- Identificar possíveis outliers e tratá-los
- Construir modelos preditivos de salário
- Avaliar o impacto de diferentes fatores nos salários

## Métodos Utilizados
- Análise exploratória de dados
- Visualizações com ggplot2
- Modelagem linear
- Remoção de outliers usando IQR
- Função de previsão salarial

## Principais Resultados
1. **Gênero não parece influenciar significativamente os salários** nos dados analisados
2. **Nível educacional mostra correlação com salários**, especialmente para doutorados
3. **Anos de experiência são o fator mais importante** na determinação do salário
4. O modelo final explica aproximadamente 71% da variação nos salários (R² = .71)

## Como Usar
O notebook inclui uma função `prever_salario()` que estima salários com base em:
```r
prever_salario(anos_experiencia, nivel_educacional)
