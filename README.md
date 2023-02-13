# Projeto 1 - Análise e limpeza de dados

**Projeto de Análise e Limpeza de Dados**

**Enunciado:**

Chegou o momento! O primeiro mini projeto que você, trainee, terá que realizar é uma limpeza e análise de dados de um dataset. Para isso, você utilizará todos os conhecimentos que adquiriu com o Turing Academy e com os cursos vistos para construir sua própria análise do zero, mas claro, sempre com ajuda e apoio de seus mentores! 

**Problema:**

Neste ano, os membros de RL do Turing USP chegaram a um consenso de que os membros do grupo não têm o melhor gosto do mundo para joguinhos, já que a maioria joga League of Legends ou Candy Crush... Extremamente triste com esta situação, o líder Berbardo decidiu fazer um estudo em cima de dados sobre avaliações de jogos na plataforma Metacritic, a fim de obter insights interessantes para ajudarem os membros a conhecerem novos jogos, para, quem sabe, fazer uma outra noite de jogos com o RH. Mais especificamente, ele busca, através dessa análise, encontrar possíveis padrões entre os jogos mais bem avaliados na plataforma.

Para isso, sabendo da sua grande reputação como um grande cientista de dados, os membros de RL requisitaram você para executar essa tarefa. Sua missão é limpar e organizar os dados que eles te enviaram e analisá-los, anotando e descrevendo cada um dos seus passos e descobertas e, ao final, elaborar uma conclusão a respeito delas. Para isso, utilize os conhecimentos adquiridos nas aulas a respeito das bibliotecas de manipulação e análise de dados.

**Informações sobre o dataset**


Esse dataset possui informações a respeito dos jogos avaliados na plataforma Metacritic. Abaixo os detalhes de cada coluna:

name - nome do jogo;

platform - plataforma do jogo;

developer - desenvolvedora do jogo;

publisher - publicadora do jogo;

genre(s) - gênero do jogo;

players - número de jogadores;

rating - avaliação ESRB;

attribute - informação adicional do jogo;

release_date - data de lançamento do jogo;

 link - url da página do jogo;
 
 critic_positive - número de reviews positivas da crítica;
 
 critic_neutral - número de reviews neutras da crítica;
 
 critic_negative  - número de reviews negativas da crítica;
 
 metascore - média do score da crítica;
 
 user_positive - número de reviews positivas dos usuários
 
 user_neutral - número de reviews neutras dos usuários;
 
 user_negative - número de reviews negativas dos usuários;
 
 user_score - média do score dos usuários.
 

**Materiais de apoio**

Caso seja necessário, não hesite em rever as aulas dadas no Turing Academy ou os cursos do Datacamp sobre os assuntos, e também não se esqueçAulas e Gravaçõesa de recorrer ao seu mentor sempre que tiver dúvidas ou precisar de ajuda! 

**Dicas**

Em uma análise é sempre necessário comentar todos os passos e descobertas, mesmo as que parecem “óbvias”, pois é importante para o leitor entender cada etapa

Não se esqueça de sempre observar se as colunas estão com os data types corretos

Para colunas categóricas verifique se os valores únicos fazem sentido

Verifique também sempre se os valores mínimos e máximos das variáveis numéricas fazem sentido para cada coluna

Os NaNs devem ser tratados apropriadamente, e nem sempre removê-los é a melhor solução

Embora a limpeza seja importante, não foque apenas nela, divida bem seu tempo para fazer também uma análise bem feita

Explore todos os tipos de gráficos possíveis na hora da análise e teste suas hipóteses com eles

Caso precise de inspiração, veja análises de outras pessoas (o Kaggle é um bom lugar para isso; o link para o dataset original retirado de lá, caso queira conferir é este, mas você deve utilizar o dataset que já foi passado acima, na primeira página deste arquivo)

Por fim, lembre-se: O objetivo desse projeto é explicar o dataset! Foque em mostrar o que ele tem de interessante, pense em plots que podem tirar boas informações (Plots por gênero/média de score, por exemplo, podem ser um bom começo) e em métricas interessantes de serem mostradas: Variância dos dados? Top jogos mais bem avaliados? Entre outras
