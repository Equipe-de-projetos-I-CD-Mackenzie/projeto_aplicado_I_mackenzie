# Script_analise_dataset
Análises de dados referente ao Dataset 
 
# *Proposta Analítica*

Nesta seção, vamos apresentar a proposta analítica, que se baseará na análise dos dados fornecidos. O objetivo principal é entender o comportamento das doações de alimentos ao longo do tempo, identificar tendências, padrões e possíveis insights que possam ser úteis para a tomada de decisões e o planejamento de futuras doações.

## *Análise Exploratória de Dados*

A análise exploratória de dados é uma etapa crucial para compreender o conjunto de dados e extrair informações relevantes. Neste estudo, utilizamos diversas ferramentas de análise de dados, incluindo visualizações gráficas e estatísticas descritivas.

### *Descrição Estatística dos Dados*

Primeiramente, realizamos uma análise descritiva dos dados para obter uma visão geral das variáveis envolvidas nas doações de alimentos. Abaixo, apresentamos algumas estatísticas-chave:

- **Quantidade:** A quantidade média de alimentos doados é de aproximadamente 3.87 unidades, variando de 1 a 12 unidades. A mediana é de 3 unidades.

- **Valor Calórico:** O valor calórico médio dos alimentos doados é de cerca de 738.42 calorias, variando de 0 a 4000 calorias. A mediana é de 380 calorias.

- **Dias Restantes:** O prazo médio de validade dos alimentos doados é de aproximadamente 658.37 dias, variando de 3 a 2596 dias. A mediana é de 567.50 dias.

Essas estatísticas iniciais nos ajudam a entender a dispersão dos dados e identificar possíveis outliers. Além disso, observamos que a quantidade mínima é 1 unidade, e o valor calórico mínimo é 0, o que pode indicar a presença de dados inconsistentes.

### *Análise Temporal das Doações*

Para entender como as doações de alimentos evoluíram ao longo do tempo, analisamos os dados relacionados às datas de doação e datas de validade.

#### *Quantidade doada por mês e ano*:

- Observamos que a quantidade de alimentos doados tende a variar ao longo dos meses e anos. Picos de doações podem ser identificados em alguns períodos, enquanto outros têm menos doações. Isso pode indicar sazonalidade nas doações ou eventos específicos que impulsionaram as doações.

#### *Quantidade por prazo de validade por mês e ano*:

- Examinamos também a relação entre a quantidade de alimentos doados e o prazo de validade. Novamente, notamos variações significativas na quantidade de alimentos doados em relação à validade. Isso pode sugerir que as doações estão correlacionadas com a proximidade da data de validade dos alimentos.

### *Correlações entre Variáveis*

Também calculamos as correlações entre as variáveis quantitativas, como quantidade, valor calórico e dias restantes. A matriz de correlação nos ajuda a entender se existe alguma relação linear entre essas variáveis.

- **Quantidade vs. Valor Calórico:** A correlação entre quantidade e valor calórico parece ser baixa, indicando que a quantidade de alimentos doados não está fortemente relacionada ao seu valor calórico.

- **Quantidade vs. Dias Restantes:** A correlação entre quantidade e dias restantes também é baixa, sugerindo que a quantidade doada não depende fortemente do prazo de validade.

### *Análise de Outliers*

Realizamos uma análise de outliers para identificar valores extremos nas variáveis quantitativas. Para isso, utilizamos diagramas de caixa (boxplots) que nos permitem visualizar a distribuição dos dados e identificar possíveis outliers.

- Identificamos outliers nas variáveis de quantidade, valor calórico e dias restantes. Esses valores atípicos podem indicar casos excepcionais de doações.

### *Análise de Categorias*

Por fim, analisamos as categorias categóricas presentes nos dados, como o tipo de alimento, o comércio (fornecedor) e o próprio alimento doado.

- **Tipo de Alimento:** Observamos a distribuição dos tipos de alimentos doados para entender quais categorias são mais comuns nas doações.

- **Maiores Fornecedores:** Identificamos os principais fornecedores (comércio) que mais contribuem com doações.

- **Maiores Alimentos:** Identificamos os alimentos individuais que são mais frequentemente doados.

Essa análise nos permite entender as preferências de doação e as parcerias mais significativas com fornecedores específicos.

Em resumo, esta seção apresentou a proposta analítica para a monografia, descrevendo as etapas de análise exploratória realizadas até o momento. A próxima seção da monografia irá aprofundar-se nas análises, explorar possíveis insights e fornecer conclusões baseadas nos resultados obtidos.

