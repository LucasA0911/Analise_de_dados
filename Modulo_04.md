# Bibliotecas para analise de dados

## [Pandas](https://pandas.pydata.org/docs/)
É uma biblioteca do Python construída sobre o Numpy focada em manipulação, análise e limpeza de dados.
### Ela trabalha com as seguintes estruturas de dados.
- DataFrame:
  - Uma tabela bidimensional com linhas e colunas, similar a uma planilha ou uma tabela SQL
- Series:
  - Um array unidimensinal rotulado capaz de armazenar qualquer tipo de dado. Um DataFrame nada mais é do que uma coleção de objetos Series que compartilham o mesmo índice.
### Se utiliza o Pandas quando:
- O trabalho envolver dados tabulares(Como arquivos CSV, Excel ou dados de um banco SQL)
- O conjunto de dados for misto, contendo colunas de texto combinadas com números e datas
- Precisar realizar tarefas de limpeza, tratamento de nulos(NaN), renomeação de colunas, reindexação ou filtros condicionais complexos.
- Estiver realizando análise exploratória de dados, agragações, ou cruzamento de tabelas. 

 ## [Numpy](https://numpy.org/doc/stable/)
 É uma biblioteca focada em processamento de arrays multidimensionais e operações matemáticas de alta performance.
 A sua principal estrutura é o **ndarray**, um array de tamanho fixo e homogêneo(todos os elementos devem ser estritamente do mesmo tipo de dado, como inteiros ou floats)
 ### Se utiliza o Numpy quando:
 - Precisar executar operações matemáticas intensivas, transformações matriciais ou álgebra linear
 - Estiver lidando com processamento de imagens ou áudio, onde os dados são nativamente representados como matrizes numéricas de pixels ou ondas.
 - O conjunto de dados for inteiramente numérico e o ganho de performance e economia de memória forem prioridade.
