# estrutura-de-dados-2-tarefa-2-und-2

Nessa atividade tem como objetivo colocar em prática o que foi visto em sala de aula sobre associatividade, conectividade, caminho e coeficiente de cluster. Utilizamos o banco de dados e o grafo do (https://github.com/alvarofpp/dataset-flights-brazil) para essa experiência e também utilizamos o framework networkx.   

1) Para fazer esse código compilar é necessário linkar o drive (vídeo ensinando como linkar o drive:https://www.youtube.com/watch?v=3696yt6JWHM), colocar o banco de dados(airports.csv) e o grafo(air_traffic.graphml) no drive e mudar o caminho dos dois  arquivos (alterar a parte "G = nx.read_graphml('/content/drive/MyDrive/est/air_traffic.graphml'" e tabémen alterar a parte "teste = csv.reader(open("/content/drive/MyDrive/est/airports.csv"))" ) .
2) As primeiras partes do código seria apenas a montagem do grafo com o banco de dados em que foi necessário adicionar as regiões como atributo e remover nodes que não possuíam regiões no banco ou apresentava erros, ou seja apenas o tratamento dos dados.
3)  A primeira questão seria o estudo sobre assortatividade e o plot do gráfico considerando o grupo como região. Analisado a assortatividade é percebido que o grafo é  não assortativo pois possui um coeficiente muito baixo.
4) A segunda questão era escolher um caminho que a atividade mandava, assim foi encontrado um com caminho de tamanho 4. O caminho escolhido ficam armazenados vários dicionários do caminho escolhido, mas na atividade deixei escrito qual foi.
5)A terceira questão foi a análise de assortatividade em relação ao degrau, pelo gráfico é percebido que o número de degrau em relação a sua vizinhança está diminuído  que quer dizer que o grafo não é assortativo e além disso o coeficiente de assortatividade pelo degrau deu negativo.  
6) A quarta questão seria sobre conectividade é foi encontrado 5 grafo conectados mas apenas 1 se conecta com muito. Além disso foi feita a contagem por região e media para cada grafo.

Grupo: Marcos Matsunaga
