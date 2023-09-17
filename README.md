# Projeto_Dados_para_abastecer_o_carro

![alt text](https://github.com/Project-4-Trends-and-Insights-Database/Projeto_Dados_para_abastecer_o_carro/blob/main/images/Squad%2007%20(2).png)

# Analytics Seven

## Visão Geral

Bem-vindo ao projeto **Analytics Seven**! Neste projeto, nossa equipe se dedica a realizar análises exploratórias profundas e significativas dos dados relacionados à série histórica de preço de venda da gasolina e do etanol no Brasil. Através da expertise da nossa equipe e das ferramentas analíticas avançadas, buscamos oferecer insights valiosos e informações relevantes para a Agência Nacional de Petróleo e Gás Natural e Biocombustíveis (ANP).

## Objetivos do Projeto

  - Realizar análises dos preços da gasolina e do etanol durante os meses de julho e agosto de 2023.
  - Responder a uma série de perguntas relevantes sobre as tendências e padrões dos preços.
  - Apresentar visualizações para ilustrar os insights obtidos.
  - Realizar limpeza e preparação dos dados para uma análise.
  

## Ferramentas utilizadas neste projeto:
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![matplotlib](https://img.shields.io/badge/matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Seaborn' src='https://img.shields.io/badge/Seaborn-100000?style=for-the-badge&logo=Seaborn&logoColor=white&labelColor=black&color=05FAFA'/></a>
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![numpy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)

## Perguntas Principais

1. Como se comportaram os preços dos combustíveis nos últimos dois meses? Houve tendências de queda ou aumento?
2. Qual é o preço médio da gasolina e do etanol durante esse período?
3. Quais são os cinco estados com os preços médios mais altos para gasolina e etanol?
4. Como variam os preços médios da gasolina e do etanol por estado?
5. Qual é o município com os preços mais baixos e mais altos para gasolina e etanol?
6. Qual é a região com o maior valor médio para a gasolina? E a menor para o etanol?
7. Existe correlação entre os valores dos combustíveis e as regiões de venda?
8. Existe correlação entre os valores dos combustíveis e as bandeiras de venda?

## Instruções de uso:
  - **1°**: Acesse o arquivo pelo link do Google Colab:
         
  - **2°**: Execute os parágrafos de código, em ordem e sem pular nenhum
  - **3°**: Importante seguir o passo anterior, caso o contrário erros ocorrerão

## Resultados Esperados

Esperamos fornecer à ANP uma análise detalhada e esclarecedora dos preços de gasolina e etanol, identificando tendências, padrões e correlações relevantes. Nossas conclusões e insights ajudarão a ANP a tomar decisões mais informadas e aprimorar sua compreensão do mercado de combustíveis.

## Conclusões da Análise Exploratória:
![alt text](https://github.com/Project-4-Trends-and-Insights-Database/Projeto_Dados_para_abastecer_o_carro/blob/main/imagens_dos_graficos/pre%C3%A7o_medio_por_estado.png)

Como podemos observar no DataFrame e visualmente no gráfico acima, temos a média de preços dos combustíveis de todos os estados brasileiros. Por diversos fatores um estado pode ter o combustível mais caro que outro, seja pela cobrança de impostos que é diferente de um estado para outro ou pela dificuldade de transporte para estados mais distantes do litoral, uma solução seria resolver o problema de infraestrutura para que o combustível possa chegar a um preço competitivo nesses locais, em especial na região Norte do país. Podemos obter as seguintes conclusões analisando o gráfico acima.
Os estados da região Norte tem a média de preço mais cara do País.
Os estados mais próximos a costa tendem a ter o preço médio menor em comparação ao restante do país, pois é onde a produção e importação dos combustíveis acontece.
O estado do Amapá possui a menor média de preço da Gasolina do país, mas por outro lado, possui o etanol mais caro.
A média de preço mais alta da Gasolina e Gasolina Aditivada é do estado do Amazonas.
O estado do Mato Grosso tem a média de preço do Etanol mais barata do Brasil. Apesar de ser o 3° maior produtor do biocombustível no Brasil.


![alt text](https://github.com/Project-4-Trends-and-Insights-Database/Projeto_Dados_para_abastecer_o_carro/blob/main/imagens_dos_graficos/regioes_mais_caras.png)


Análisando o gráfico podemos perceber que a região norte tem a Gasolina mais cara do país, enquanto que a região sudeste tem a média mais barata do Brasil. Mas em todas as regiões os preços médios se mantém acima de R$ 5,50.



![alt text](https://github.com/Project-4-Trends-and-Insights-Database/Projeto_Dados_para_abastecer_o_carro/blob/main/imagens_dos_graficos/municipio_maior_valor.png)


Com o DataFrame e o gráfico acima, agora temos os municípios com o maior preço de combustível do Brasil. Como ja mencionado em analises anteriores os estados do norte do país são os que estão sempre acima da média dos valores de combustíveis em relação aos outros estados brasileiros. Podemos então concluir com esta análise que:

Tefe do estado do Amazonas é o município com a Gasolina Aditivada mais cara do Brasil.
Cruzeiro do Sul do estado do Acre, é o município com o Etanol mais caro do país.
Tefe novamente também do estado do Amazonas, é o município com a Gasolina mais cara do Brasil.
Ambas os municípios citados são distantes dos centros de distribuição de combustíveis, dificultando o transporte para esses locais.


![alt text](https://github.com/Project-4-Trends-and-Insights-Database/Projeto_Dados_para_abastecer_o_carro/blob/main/imagens_dos_graficos/municipio_menor_valor.png)


Ao observar nosso DataFrame e o gráfico acima, podemos conhecer quais são os municípios onde cada tipo de combustível é o mais barato do país. O interessante de se notar é que todos são municípios do estado de São Paulo. Podemos concluir que os municípios com o menor preço de combustíveis são:
Diadema (SP) com a gasolina aditivada mais barata do Brasil.
SANTA BARBARA D'OESTE (SP) com o etanol mais barato do Brasil.
Sorocaba (SP) com a Gasolina mais barata do Brasil.
Alguns pontos prováveis de se explicar o porque de apenas terem municípios do estado de São Paulo nessa análise são:

O sudeste é a segunda região em que a média é a mais baixa de cobrança de ICMS.
São Paulo é o maior produtor de Cana-de-açúcar do Brasil com 54,1% da quantidade produzida na safra 2020/21.
São Paulo é onde se concentra o maior número de refinarias no Brasil, aproximadamente 38% da capacidade de refino nacional.



