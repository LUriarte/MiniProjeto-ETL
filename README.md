# MiniProjeto-ETL
Meu primeiro projeto de ETL e análise de dados, desenvolvido durante o curso de Engenharia de Dados na SoulCode Academy, em novembro de 2021. O banco de dados utilizado compreende informações acerca das vendas de uma grande empresa do setor alimentício. 

## Ferramentas utilizadas:
* Linguagem de programação Python
* Linguagem de programação SQL
* Bibliotecas Pandas e PySpark
 
## Metodologia:
* Pandas
  - Importação de banco de dados em CSV e criação de Data Frame utilizando a biblioteca Pandas 
  - Renomeação de colunas, traduzindo de inglês para português
  - Verificação de inconsistências em cada coluna
  - Alteração de valores, deletar colunas que não serão utilizadas
* PySpark
  - Importação e criação do Dataframe de PySpark a partir do DataFrame de Pandas, utilizando o Struct Type para montar o esquema do DataFrame
  - Criação de duas novas colunas a partir dos dados disponíveis, auxiliando as análises
  - Reordenação das colunas
* Consultas PySpark e SparkSQL
  -  Consultas simples utilizando a sintaxe PySpark e em sequência a sintaxe Standard SQL através do método spark.sql
  -  Consultas utilizando médias, somas, filtros, ordenação, buscando insights acerca do perfil de clientes, melhores canais de venda, produtos em destaque etc 
