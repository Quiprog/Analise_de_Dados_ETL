
Bootcamp - Cognizant Cloud Data Engineer

Curso - Analise de dados com Python e Pandas
 
Projeto - Desenvolvimento da capacidade de se trabalhar com dados do tipo planilha

INTRODUCAO:
Nesse projeto, ao longo das diversas etapas como: busca na internet, carregamento, fracionamento, juncao, limpeza do dados, manipulacao, 
geracao de graficos e exportacao, foi possível desenvolver a capacidade de trabalhar com dados do tipo planilha.

BUSCA NA INTERNET: Nesse processo buscou-se encontrar uma planilha que pudesse abranger as etapas descritas na introducao. Encontrar tal planilha nao foi tao facil
pois, em muitas delas havia muitos dados faltantes nas colunas e em outras havia dificuldades em se encontrar dados relevantes para analise.

CARREGAMENTO: Definida a planilha para trabalho efetuou-se o carregamento explorando dois tipos de carregamento: o primeiro baixando-se o arquivo num diretório do 
meu notebook e fazendo o carregamento por meio de "from google.colab import files", ja no segundo foi feito o upload do arquivo numa pasta dentro colab notebook e 
posteriormente o carregamento.

FRACIONAMENTO: Aqui o arquivo hotel_bookings.csv foi desmembrado em tres, com base nos anos 2015, 2016 e 2017 e os arquivos hotel_bookings_2015.csv, 
hotel_bookings_2016.csv e hotel_bookings_2017.csv foram criados.

JUNCAO: Neste momento se atribuiu aos tres arquvios acima as variaveis df1, df2 e df3 e pois do comando "df = pd.concat([df1,df2,df3])" foi feita a juncao.

LIMPEZA DE DADOS: Nesta etapa se verificou que em algumas colunas havia muitos dados faltantes e para essas optou-se por exclui-las. Outras que antes 
da exclusao das citadas acima apresentavam poucos dados faltantes, com a exclusao destas colunas acabaram por excluir os poucos dados faltantes destas ultimas.
Nas colunas, com poucos dados faltantes que restaram, sem comprometer significativamente os dados do dataframe, optou-se por excluir as linhas das quais havia
dados faltantes.

MANIPULACAO: Aqui alguns formatos de dados foram alterados, "count", "groupby", "sum" e "mean" foram trabalhados nesta etapa.

GERACAO DE GRAFICOS: Aqui trabalho-se com os graficos de barra e tipo "pizza" envolvendo a inclusao de titulo, eixos e tamanho nos dois tipos de graficos.

EXPORTACAO: Esta pratica foi concretizada quando se efetuou o fracionamento do arquivo hotel_bookings.csv

CONCLUSAO: A execucao deste projeto proporcionou a solidificacao dos conceitos aprendidos neste projeto e em aulas anteriores deste bootcamp e agucar nosso interesse
em se aprofundar nesta area de conhecimento.

Obs1.: Colunas.docx e um arquivo de texto que descreve todas as colunas do hotel_bookings.csv e destacando aquelas que foram excluidas ao longo deste projeto.
Obs2.: Nesse projeto trabalho com o Python 3.7.12 e o Google Colab

