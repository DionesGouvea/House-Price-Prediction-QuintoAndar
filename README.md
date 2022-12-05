
## **Desafio de Regressão do QuintoAndar em parceria com a Tera**

**Autor:** Diones Gouvea 

**Linguagem:** Python

**Notebook:** [Modelo de precificação de Imoveis](https://github.com/DionesGouvea/House-Price-Prediction-QuintoAndar/blob/main/Precifica%C3%A7%C3%A3o_de_im%C3%B3veis_Quinto_Andar.ipynb)

--------------------------------------------------------------------------------

### **Contexto analítico**

A área de marketing do QuintoAndar quer montar uma calculadora de preço (como esta [aqui: https://mkt.quintoandar.com.br/quanto-cobrar-de-aluguel/), e nesse projeto, os analistas negociais e corretores querem, também, entender as principais variáveis e características chaves que influenciam no valor de venda do imóvel (Ex: quantificar o impacto do aumento da área do imóvel no preço, ou quantificar o impacto de ter piscina, ou não no preço)

**Objetivo 1**, interpretabilidade: construir uma regressão linear simples, com poucas variáveis importantes, visando gerar insights para corretores e proprietários no quesito precificação dos imóveis. Ou seja, o foco será na interpretação dos coeficientes (ex: se aumentar a área do imóvel em uma unidade isso irá aumentar em Y o preço deste imóvel).

**Objetivo 2**, predição: construir um modelo com alto poder preditivo, com mais variáveis, visando um bom desempenho e com o intuito de ser usado em uma página web como a calculadora de preço.

### **Resumo do projeto**
Esse desafio foi construído em parceria entre a Tera e o QuintoAndar, onde o objetivo é simular um projeto de machine learning com características semelhantes ao que ocorre no dia a dia da empresa. O conjunto de dados descreve a venda de propriedades residenciais individuais de uma cidade americana, de 2006 a 2010 contendo 80 variáveis. O modelo de randomForest se mostrou eficiente antes mesmo de uma busca por melhores parâmetros, após aplicarmos os melhores parâmetros e reduzir para apenas as 25 variáveis mais importantes conseguimos um Erro absoluto médio de 14.048 e um MAPE de 8%.


---------------------------------------------------------------------------------------------------------------------------------------------------------
Palavras-Chave: <em>Pacote Pandas, Numpy, Seaborn; Técnicas de Análise Exploratória de Dados; Regras de Negócios; Identificação de Outliers; Engeenering Feature; Dummy; RepeatedK-Fold; MAE, GridSearch; RandomForest; Tunagem de Hiperparâmetros; Insigths dos problema.</em>
