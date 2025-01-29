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
    *   Decidir como lidar com os valores ausentes sem prejudicar os dados.
4.  **Visualização de Dados:**
    *   Criar gráficos para melhor compreensão das variáveis.
5.  **Análise de Sobrevivência:**
    *   Determinar a taxa geral de sobrevivência.
    *   Analisar se a taxa de sobrevivência varia entre homens e mulheres.
    *   Investigar se a idade influencia na taxa de sobrevivência.

## Conclusão

**Análise Descritiva:**

*   **Idades:** Havia uma ampla faixa etária entre os passageiros, desde bebês até idosos de 76 anos.
*   **Tarifas:** Os valores das tarifas pagas pelos passageiros variavam bastante, com um intervalo considerável entre os menores e maiores valores.
*   **Sobrevivência:** A taxa de sobrevivência média foi de aproximadamente 36%.
*   **Classes:** Havia uma quantidade maior de passageiros da 3ª classe em comparação com as outras classes.

**Visualização de Dados:**

*   **Relação Classe e Tarifa:** A tarifa parece estar fortemente relacionada à classe da cabine, com passageiros da 1ª classe pagando as tarifas mais altas.
*   **Gênero e Tarifa:** A relação entre gênero e tarifa não parece ser tão forte quanto a relação entre classe e tarifa.
*   **Embarque e Tarifa:** Os passageiros de Cherbourg tendiam a pagar mais caro que os de Southampton e Queenstown.
*   **Distribuição de Idade por Gênero:** Observa-se que a mediana de idade dos homens é ligeiramente superior à das mulheres, e que há uma concentração maior de homens entre os 20 e 40 anos. No geral, a faixa etária de ambos é bem similar.

**Sobrevivência:**

*   **Sobrevivência por Classe:** A taxa de sobrevivência foi maior para os passageiros da 1ª classe, seguido pelos da 2ª e 3ª classes.
*   **Sobrevivência por Gênero:** As mulheres tiveram uma taxa de sobrevivência superior aos homens.
*   **Sobrevivência por Faixa Etária:** Os dados sugerem que as faixas etárias de bebês (0-10) e idosos (70-80) apresentaram taxas de sobrevivência mais elevadas, o que pode indicar um esforço para priorizar essas faixas na hora do resgate.

**Implicações:**

*   **Classe Social:** A classe social teve uma influência significativa tanto no custo da passagem como nas chances de sobrevivência.
*   **Gênero:** A priorização de mulheres e crianças no resgate pode ser evidente, dado que nenhuma sobrevivência masculina foi observada no dataset.
*   **Porto de Embarque:** As pessoas que embarcaram em Queenstown quase não adquiriram assentos na 1ª classe, provavelmente pela classe social da população daquela cidade à época.
