# Análise exploratória do dataset Titanic 🚢

## Objetivos
1.  **Carregamento e Inspeção Inicial:**
    *   Carregar o dataset usando Pandas.
    *   Exibir as primeiras e últimas linhas do dataset.
    *   Verificar o tamanho do dataset (número de linhas e colunas).
    *   Exibir informações sobre os tipos de dados e valores não nulos.
2.  **Estatísticas Descritivas:**
    *   Calcular as estatísticas descritivas para as variáveis numéricas (média, mediana, desvio padrão, mínimo, máximo, quartis).
    *   Calcular a contagem de valores para as variáveis categóricas (sexo, classe, porto de embarque).
3.  **Análise de Valores Ausentes:**
    *   Identificar as colunas com valores ausentes.
    *   Decidir como lidar com os valores ausentes (preencher com a média, mediana, remover as linhas, etc.). Justificar sua escolha.
4.  **Visualização de Dados:**
    *   Criar histogramas para as variáveis numéricas (idade, tarifa).
    *   Criar gráficos de barras para as variáveis categóricas (sexo, classe, porto de embarque, sobreviventes).
    *   Criar um gráfico de dispersão para relacionar duas variáveis numéricas (idade e tarifa, por exemplo).
    *   Criar boxplots para comparar a distribuição de uma variável numérica entre diferentes grupos (idade por sexo, tarifa por classe, etc.).
5.  **Análise de Sobrevivência:**
    *   Determinar a taxa geral de sobrevivência.
    *   Analisar se a taxa de sobrevivência varia entre homens e mulheres.
    *   Analisar se a taxa de sobrevivência varia entre as diferentes classes de passageiros.
    *   Investigar se a idade influencia na taxa de sobrevivência.
    *   Investigar se o porto de embarque influencia na taxa de sobrevivência.
    *   Utilizar gráficos para ilustrar as descobertas.

## Conclusão

Pude responder e chegar às seguintes conclusões:
- Houveram diversos sobreviventes, cerca de `37%` dos passageiros, sendo todos do gênero feminino (desde bebês até idosas).
- A maior parte dos passageiros são de `Southampton`.
- Nenhum passageiro de `Queenstown` adquiriu uma cabine de 1ª Classe, talvez pela cidade possuir habitantes de classe inferior naquela época.
- Não houveram homens sobreviventes, provavelmente por dar prioridade e salvar vidas de bebês, crianças, mulheres e idosos.
