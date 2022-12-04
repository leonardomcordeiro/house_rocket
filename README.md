# House Rocket Inc

### Geração de insight com Análise Exploratória de Dados

![cover](https://github.com/leonardomcordeiro/house_rocket/blob/main/images/seattle_cover.jpg)

Neste repositório você encontrará como a análise exploratória de dados e dashboards podem gerar valor a uma empresa do setor imobiliário.

Os dados utilizados neste projeto podem ser econtrados no [Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/discussion/207885) e mais detalhes [aqui](https://info.kingcounty.gov/assessor/esales/Glossary.aspx). Algumas informações adicionais foram criadas para contextualizar o problema de negócio.


## 1. O Problema de Negócio

A House Rocket Real State Inc é uma empresa localizada em São Paulo e atua no ramo imobiliário. Especializada na compra e venda de imóveis e deseja ampliar os seus negócios passando a atuar nos EUA, mais especificamente no condado de King, Washington.

Antes de começar suas atividades internacionais, o CEO da House Rocket precisa compreender melhor o mercado imobiliário de King, e para isso forneceu ao time de data science, uma base de dados com diversas características sobre imóveis de King. A partir desses dados, é esperado que sejam gerados insights como:


• Quais propriedades a empresa deve comprar.

• Uma visualização de mapa com propriedades disponíveis.

• Uma exibição de tabela com filtros de atributos.

• Lucro esperado de cada propriedade.

### Descrição dos dados:
• id - ID único para cada casa vendida

• data - Data da venda da casa

• price - Preço de cada casa vendida

• bedrooms - Número de quartos

• bathrooms - Número de banheiros, onde 0,5 corresponde a um quarto com banheiro, mas sem chuveiro

• sqft_living - Metragem quadrada do espaço interior dos apartamentos

• sqft_lot - Metragem quadrada do espaço do terreno

• floors - Número de andares

• waterfront - Uma variável fictícia para saber se o apartamento tinha vista para a orla ou não

• view - Um índice de 0 a 4 de quão boa era a visão da propriedade. Onde: 0 = Sem vista, 1 = Razoável 2 = Média, 3 = Boa, 4 = Excelente

• condition - Um índice de 1 a 5 sobre a condição do apartamento, Um índice de 1 a 5 sobre a condição do apartamento: 1 = Ruim- Desgastado, 2 = Razoável- Mal gasto, 3 = Médio, 4 = Bom, 5= Muito Bom

• grade - Um índice de 1 a 13, onde 1-3 fica aquém da construção e design de edifícios, 7 tem um nível médio de construção e design e 11-13 tem um alto nível de qualidade de construção e design.

• sqft_above - A metragem quadrada do espaço interno da habitação que está acima do nível do solo

• sqft_basement - A metragem quadrada do espaço interno da habitação que está abaixo do nível do solo

• yr_built - O ano em que a casa foi inicialmente construída

• yr_renovated - O ano da última reforma da casa

• zipcode - Em que área do CEP a casa está

• lat - latitude

• long - longitude

• sqft_living15 - A metragem quadrada do espaço interno da habitação para os 15 vizinhos mais próximos

• sqft_lot15 - A metragem quadrada dos terrenos dos 15 vizinhos mais próximos


## 2. Premissas de Negócio


 • Para o primeiro ciclo, são considerados apenas banheiros com chuveiro. Exemplo: 2 banheiros, mas um apenas com lavabo, será considerado 1 banheiro.
 
 • Imóveis com 0 quartos foram retirados da amostra, por não se tratarem de imóveis residenciais.
 
 • Subgrupos de imóveis com amostragem inferior a 100, para banheiro e quarto, foram retirados da amostra. Receberão análise específica em um próximo ciclo.
 
 • Imóveis com ano de reforma zero igual a zero (yr_renovated = 0) foi presumido que não houve nenhuma reforma.
 
 
 
 


## 3. Estratégia de Solução

## 4. Os 3 Principais Insights

## 5. Conclusão

## 6. Next Step

