
## 🔍 Etapas da análise
### 1. Perfil geral dos dados 
- Dimensões (linhas/colunas)
- Tipos de dados
- Valores nulos e duplicados
- Estatísticas descritivas 

### 2. Verificando relação entre gorjetas por quantidade de pessoas
- total_bill, size, tip
- Gráficos: boxplot e scatterplot
- Pergunta: existe correlação? forte ou fraca? positiva ou negativa?

![Relação de Grojetas por Grupos](../outputs/figures/GorjetasxQtdPessoas.png)

- Ao analisar a distribuição da gorjeta por tamanho do grupo, observamos que os outliers não estão distribuidos igualmente entre os grupos, ele se concentram principalmente nos grupos de tamanhos 2, 3, 4 e 6, enquanto o grupo de tamanho 1 não apresenta nenhum outlier visível.

- Também percebemos que conforme o tamanho do grupo aumenta, maior a mediana é, mas não necessariamente os outliers aumentam junto...

- Temos uma mediana bem baixa no grupo 1, de ~$1.4 de gorjeta, o que sugere que quando se está sozinho a gorjeta é bem mais previsivel.

- Também podemos reparar que a caixa representante aos grupos de 4 pessoas é mais larga, a distância entre primeiro e o terceiro quartil dela é o maior entre as caixas, talvez isso tudo indique que em grupos de quatro pessoas a gorjeta varie mais.

- Temos também a percepção de que o maior outlier está nos grupos de 3 pessoas, e também a variação de gorjeta ser maior nele do que nos grupos de 6 pessoas (o que seria mais intuitivo, já que grupos maiores teoricamente gastariam mais e suas gosrjetas concequentemente seriam maiores).

### 3. Distribuição das variáveis numéricas e categóricas
- total_bill, tip, size, smoker, time, day
- Gráficos: relplot e countplot
- Perguntas: os dados parecem normais? há assimetria? existem outliers?

![Distribuição da variáveis entre Almoço e Jantar](../outputs/figures/Distribuicao_variaveis_LunchxDinner.png)
