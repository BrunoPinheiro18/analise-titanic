# 🚢 Análise e Limpeza de Dados — Titanic

## Descrição
Limpeza profunda e análise exploratória do famoso dataset do Titanic,
identificando os factores que influenciaram a sobrevivência dos passageiros.

## Objectivos
- Limpar e tratar os dados em falta
- Analisar a taxa de sobrevivência por género, classe e idade
- Identificar padrões que determinaram quem sobreviveu

## Limpeza realizada
- ❌ Eliminada coluna **Cabin** (77% de valores nulos)
- ✅ **Age** preenchida com a mediana (28 anos)
- ✅ **Embarked** preenchida com a moda (Southampton)

## Principais Insights
- ⚰️ Apenas **38.4%** dos passageiros sobreviveu
- 👩 Mulheres tiveram **74%** de taxa de sobrevivência vs **19%** dos homens
- 🎩 1ª Classe: **63%** | 2ª Classe: **47%** | 3ª Classe: **24%**
- 👶 Crianças tiveram maior prioridade de sobrevivência

## Ferramentas utilizadas
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Como executar
1. Clona o repositório
2. Instala as dependências: `pip install pandas matplotlib seaborn`
3. Abre o ficheiro `.ipynb` no Jupyter Notebook
